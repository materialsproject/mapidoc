A dict of Crystallographic Information File (CIF) format strings for the material. This includes the conventional, primitive and refined cells.

The **primitive** cell is an economical representation for a structure, in
terms of number of sites. Thus, this unit cell is typically of interest to
theorists for efficient calculations. Reference [1] describes the method we use
to define a primitive cell.

The **conventional standard** structure follows a conventional practice to
define a cell so that it is more readable / visually understandable to a human
being. Experimentalists are typically more comfortable with this
format. Reference [1] describes this standard as well.

The **computed** cell is that computed by MP. It is identical to either the
primitive or conventional standard cells, the other being the result of a
transformation of this cell.

The **refined**, aka **symmetrized** structure, is a modification of the
conventional standard cell to express detected symmetry. Sites are moved
relative to the energy-relaxed conventional standard cell. Some theorists
prefer this form for "cleaner" band structure calculations. We use
[pymatgen](http://pymatgen.org/)'s
`pymatgen.symmetry.analyzer.SpacegroupAnalyzer` via
`pymatgen.io.cifio.CifWriter` (with `symprec=0.1`) to generate this CIF.

[1] Wahyu Setyawan, Stefano Curtarolo, High-throughput electronic band structure calculations: Challenges and tools, Computational Materials Science, Volume 49, Issue 2, August 2010, Pages 299-312, ISSN 0927-0256,
[http://dx.doi.org/10.1016/j.commatsci.2010.05.010](http://dx.doi.org/10.1016/j.commatsci.2010.05.010).

## Example response in JSON

```json
{
    "primitive" : "# generated using pymatgen\ndata_LuAl2\n_symmetry_space_group_name_H-M   'P 1'\n_cell_length_a   5.48873905\n_cell_length_b   5.48873905\n_cell_length_c   5.48873905\n_cell_angle_alpha   60.00000000\n_cell_angle_beta   60.00000000\n_cell_angle_gamma   60.00000000\n_symmetry_Int_Tables_number   1\n_chemical_formula_structural   LuAl2\n_chemical_formula_sum   'Lu2 Al4'\n_cell_volume   116.923754737\n_cell_formula_units_Z   2\nloop_\n _symmetry_equiv_pos_site_id\n _symmetry_equiv_pos_as_xyz\n  1  'x, y, z'\nloop_\n _atom_site_type_symbol\n _atom_site_label\n _atom_site_symmetry_multiplicity\n _atom_site_fract_x\n _atom_site_fract_y\n _atom_site_fract_z\n _atom_site_occupancy\n  Lu  Lu1  1  0.250000  0.250000  0.250000  1\n  Lu  Lu2  1  0.000000  0.000000  0.000000  1\n  Al  Al3  1  0.125000  0.625000  0.625000  1\n  Al  Al4  1  0.625000  0.625000  0.625000  1\n  Al  Al5  1  0.625000  0.125000  0.625000  1\n  Al  Al6  1  0.625000  0.625000  0.125000  1\n",
    "refined" : "# generated using pymatgen\ndata_LuAl2\n_symmetry_space_group_name_H-M   'P 1'\n_cell_length_a   7.76224920\n_cell_length_b   7.76224920\n_cell_length_c   7.76224920\n_cell_angle_alpha   90.00000000\n_cell_angle_beta   90.00000000\n_cell_angle_gamma   90.00000000\n_symmetry_Int_Tables_number   1\n_chemical_formula_structural   LuAl2\n_chemical_formula_sum   'Lu8 Al16'\n_cell_volume   467.69501895\n_cell_formula_units_Z   8\nloop_\n _symmetry_equiv_pos_site_id\n _symmetry_equiv_pos_as_xyz\n  1  'x, y, z'\nloop_\n _atom_site_type_symbol\n _atom_site_label\n _atom_site_symmetry_multiplicity\n _atom_site_fract_x\n _atom_site_fract_y\n _atom_site_fract_z\n _atom_site_occupancy\n  Lu  Lu1  1  0.250000  0.750000  0.750000  1\n  Lu  Lu2  1  0.000000  0.000000  0.000000  1\n  Lu  Lu3  1  0.250000  0.250000  0.250000  1\n  Lu  Lu4  1  0.000000  0.500000  0.500000  1\n  Lu  Lu5  1  0.750000  0.750000  0.250000  1\n  Lu  Lu6  1  0.500000  0.000000  0.500000  1\n  Lu  Lu7  1  0.750000  0.250000  0.750000  1\n  Lu  Lu8  1  0.500000  0.500000  0.000000  1\n  Al  Al9  1  0.625000  0.875000  0.875000  1\n  Al  Al10  1  0.625000  0.625000  0.625000  1\n  Al  Al11  1  0.375000  0.125000  0.875000  1\n  Al  Al12  1  0.375000  0.875000  0.125000  1\n  Al  Al13  1  0.625000  0.375000  0.375000  1\n  Al  Al14  1  0.625000  0.125000  0.125000  1\n  Al  Al15  1  0.375000  0.625000  0.375000  1\n  Al  Al16  1  0.375000  0.375000  0.625000  1\n  Al  Al17  1  0.125000  0.875000  0.375000  1\n  Al  Al18  1  0.125000  0.625000  0.125000  1\n  Al  Al19  1  0.875000  0.125000  0.375000  1\n  Al  Al20  1  0.875000  0.875000  0.625000  1\n  Al  Al21  1  0.125000  0.375000  0.875000  1\n  Al  Al22  1  0.125000  0.125000  0.625000  1\n  Al  Al23  1  0.875000  0.625000  0.875000  1\n  Al  Al24  1  0.875000  0.375000  0.125000  1\n",
    "computed" : "# generated using pymatgen\ndata_LuAl2\n_symmetry_space_group_name_H-M   'P 1'\n_cell_length_a   5.48873905\n_cell_length_b   5.48873905\n_cell_length_c   5.48873905\n_cell_angle_alpha   60.00000005\n_cell_angle_beta   60.00000003\n_cell_angle_gamma   60.00000007\n_symmetry_Int_Tables_number   1\n_chemical_formula_structural   LuAl2\n_chemical_formula_sum   'Lu2 Al4'\n_cell_volume   116.923754737\n_cell_formula_units_Z   2\nloop_\n _symmetry_equiv_pos_site_id\n _symmetry_equiv_pos_as_xyz\n  1  'x, y, z'\nloop_\n _atom_site_type_symbol\n _atom_site_label\n _atom_site_symmetry_multiplicity\n _atom_site_fract_x\n _atom_site_fract_y\n _atom_site_fract_z\n _atom_site_occupancy\n  Al  Al1  1  0.500000  0.500000  0.500000  1\n  Al  Al2  1  0.500000  0.500000  0.000000  1\n  Al  Al3  1  0.000000  0.500000  0.500000  1\n  Al  Al4  1  0.500000  0.000000  0.500000  1\n  Lu  Lu5  1  0.875000  0.875000  0.875000  1\n  Lu  Lu6  1  0.125000  0.125000  0.125000  1\n",
    "conventional_standard" : "# generated using pymatgen\ndata_LuAl2\n_symmetry_space_group_name_H-M   'P 1'\n_cell_length_a   7.76224920\n_cell_length_b   7.76224920\n_cell_length_c   7.76224920\n_cell_angle_alpha   90.00000000\n_cell_angle_beta   90.00000000\n_cell_angle_gamma   90.00000000\n_symmetry_Int_Tables_number   1\n_chemical_formula_structural   LuAl2\n_chemical_formula_sum   'Lu8 Al16'\n_cell_volume   467.69501895\n_cell_formula_units_Z   8\nloop_\n _symmetry_equiv_pos_site_id\n _symmetry_equiv_pos_as_xyz\n  1  'x, y, z'\nloop_\n _atom_site_type_symbol\n _atom_site_label\n _atom_site_symmetry_multiplicity\n _atom_site_fract_x\n _atom_site_fract_y\n _atom_site_fract_z\n _atom_site_occupancy\n  Lu  Lu1  1  0.250000  0.750000  0.750000  1\n  Lu  Lu2  1  0.000000  0.000000  0.000000  1\n  Lu  Lu3  1  0.250000  0.250000  0.250000  1\n  Lu  Lu4  1  0.000000  0.500000  0.500000  1\n  Lu  Lu5  1  0.750000  0.750000  0.250000  1\n  Lu  Lu6  1  0.500000  0.000000  0.500000  1\n  Lu  Lu7  1  0.750000  0.250000  0.750000  1\n  Lu  Lu8  1  0.500000  0.500000  0.000000  1\n  Al  Al9  1  0.625000  0.875000  0.875000  1\n  Al  Al10  1  0.625000  0.625000  0.625000  1\n  Al  Al11  1  0.375000  0.125000  0.875000  1\n  Al  Al12  1  0.375000  0.875000  0.125000  1\n  Al  Al13  1  0.625000  0.375000  0.375000  1\n  Al  Al14  1  0.625000  0.125000  0.125000  1\n  Al  Al15  1  0.375000  0.625000  0.375000  1\n  Al  Al16  1  0.375000  0.375000  0.625000  1\n  Al  Al17  1  0.125000  0.875000  0.375000  1\n  Al  Al18  1  0.125000  0.625000  0.125000  1\n  Al  Al19  1  0.875000  0.125000  0.375000  1\n  Al  Al20  1  0.875000  0.875000  0.625000  1\n  Al  Al21  1  0.125000  0.375000  0.875000  1\n  Al  Al22  1  0.125000  0.125000  0.625000  1\n  Al  Al23  1  0.875000  0.625000  0.875000  1\n  Al  Al24  1  0.875000  0.375000  0.125000  1\n"
}
```

