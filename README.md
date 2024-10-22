# data_example

An example for the dataframe needed is given in `dataframe.pkl`. It is pickled Pandas DataFrame that can be read in by,

```
pandas.read_pickle('dataframe.pkl')
```

There are four columns-

- `name`: string, a string which gives a name to the given structure
- `atoms`: an ASE atoms object, which contains the atomic structure
- `energy`: float, energy of the structure in eV
- `forces`: 3xN array, forces on each atom in eV/Angstrom
- `number_of_atoms`: int, number of atoms in each structure (optional)
