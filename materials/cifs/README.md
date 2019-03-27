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
    "computed": "# generated using pymatgen\ndata_Te\n_symmetry_space_group_name_H-M   P3_121\n_cell_length_a   4.51237418\n_cell_length_b   4.51237418\n_cell_length_c   5.95989883\n_cell_angle_alpha   90.00000000\n_cell_angle_beta   90.00000000\n_cell_angle_gamma   120.00000000\n_symmetry_Int_Tables_number   152\n_chemical_formula_structural   Te\n_chemical_formula_sum   Te3\n_cell_volume   105.09443754\n_cell_formula_units_Z   3\nloop_\n _symmetry_equiv_pos_site_id\n _symmetry_equiv_pos_as_xyz\n  1  'x, y, z'\n  2  '-y, x-y, z+1/3'\n  3  '-x+y, -x, z+2/3'\n  4  'y, x, -z'\n  5  'x-y, -y, -z+2/3'\n  6  '-x, -x+y, -z+1/3'\nloop_\n _atom_site_type_symbol\n _atom_site_label\n _atom_site_symmetry_multiplicity\n _atom_site_fract_x\n _atom_site_fract_y\n _atom_site_fract_z\n _atom_site_occupancy\n  Te  Te1  3  0.000000  0.268950  0.666667  1\n",
    "conventional_standard": "# generated using pymatgen\ndata_Te\n_symmetry_space_group_name_H-M   P3_121\n_cell_length_a   4.51237418\n_cell_length_b   4.51237418\n_cell_length_c   5.95989883\n_cell_angle_alpha   90.00000000\n_cell_angle_beta   90.00000000\n_cell_angle_gamma   120.00000000\n_symmetry_Int_Tables_number   152\n_chemical_formula_structural   Te\n_chemical_formula_sum   Te3\n_cell_volume   105.09443754\n_cell_formula_units_Z   3\nloop_\n _symmetry_equiv_pos_site_id\n _symmetry_equiv_pos_as_xyz\n  1  'x, y, z'\n  2  '-y, x-y, z+1/3'\n  3  '-x+y, -x, z+2/3'\n  4  'y, x, -z'\n  5  'x-y, -y, -z+2/3'\n  6  '-x, -x+y, -z+1/3'\nloop_\n _atom_site_type_symbol\n _atom_site_label\n _atom_site_symmetry_multiplicity\n _atom_site_fract_x\n _atom_site_fract_y\n _atom_site_fract_z\n _atom_site_occupancy\n  Te  Te1  3  0.000000  0.268950  0.666667  1\n",
    "primitive": "# generated using pymatgen\ndata_Te\n_symmetry_space_group_name_H-M   'P 1'\n_cell_length_a   4.51237418\n_cell_length_b   4.51237418\n_cell_length_c   5.95989883\n_cell_angle_alpha   90.00000000\n_cell_angle_beta   90.00000000\n_cell_angle_gamma   120.00000000\n_symmetry_Int_Tables_number   1\n_chemical_formula_structural   Te\n_chemical_formula_sum   Te3\n_cell_volume   105.09443754\n_cell_formula_units_Z   3\nloop_\n _symmetry_equiv_pos_site_id\n _symmetry_equiv_pos_as_xyz\n  1  'x, y, z'\nloop_\n _atom_site_type_symbol\n _atom_site_label\n _atom_site_symmetry_multiplicity\n _atom_site_fract_x\n _atom_site_fract_y\n _atom_site_fract_z\n _atom_site_occupancy\n  Te  Te1  1  0.268950  0.000000  0.333333  1\n  Te  Te2  1  0.000000  0.268950  0.666667  1\n  Te  Te3  1  0.731050  0.731050  0.000000  1\n",
    "refined": "# generated using pymatgen\ndata_Te\n_symmetry_space_group_name_H-M   P3_121\n_cell_length_a   4.51237418\n_cell_length_b   4.51237418\n_cell_length_c   5.95989883\n_cell_angle_alpha   90.00000000\n_cell_angle_beta   90.00000000\n_cell_angle_gamma   120.00000000\n_symmetry_Int_Tables_number   152\n_chemical_formula_structural   Te\n_chemical_formula_sum   Te3\n_cell_volume   105.09443754\n_cell_formula_units_Z   3\nloop_\n _symmetry_equiv_pos_site_id\n _symmetry_equiv_pos_as_xyz\n  1  'x, y, z'\n  2  '-y, x-y, z+1/3'\n  3  '-x+y, -x, z+2/3'\n  4  'y, x, -z'\n  5  'x-y, -y, -z+2/3'\n  6  '-x, -x+y, -z+1/3'\nloop_\n _atom_site_type_symbol\n _atom_site_label\n _atom_site_symmetry_multiplicity\n _atom_site_fract_x\n _atom_site_fract_y\n _atom_site_fract_z\n _atom_site_occupancy\n  Te  Te1  3  0.000000  0.268950  0.666667  1\n"
}
```

