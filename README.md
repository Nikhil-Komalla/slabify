# slabs.py
## Linux Installation steps

1. Go to home (cd ~)
2. pip install pymatgen
3. copy slabs.py on to the location where you want to get surfaces.
4. Use the following command:
   ```bash
   python slabs.py input=CONTCAR miller=100 symmetry=False thickness=10 vacuum=15 output=0
   ```
   (you can search "#usage" to search for command line in the code)
