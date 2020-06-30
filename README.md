# HASYDataSet
Image data set for Latex characters. Training folders has 1,51,241 images with 369 classes
Download Link(zip):  




Files
```bash
symbols.csv: List of all symbols with corresponding symbol_id
```

## Folder Structure:
```bash
├── Train
├── Validation
└── symbols.csv
```
### Folders Folder

```bash
Train
├── 100
├── 1000
├── 1004
├── 1005
├── 1006
├── 1007
├── 1008
├── 101
├── 1010
.
.
.
```
Each folder is named after the symbol.id in symbols.csv, it contains all the images with the symbol in it:

```
999
├── v2-150681.png
├── v2-150682.png
├── v2-150683.png
├── v2-150684.png
├── v2-150685.png
├── v2-150686.png
├── v2-150687.png
├── v2-150688.png
├── v2-150689.png
├── v2-150690.png
├── v2-150691.png
├── v2-150692.png
├── v2-150693.png
├── v2-150694.png
├── v2-150695.png
├── v2-150696.png
├── v2-150697.png
├── v2-150698.png
├── v2-150699.png
├── v2-150700.png
├── v2-150701.png
├── v2-150702.png
├── v2-150703.png
├── v2-150704.png
├── v2-150705.png
├── v2-150706.png
├── v2-150707.png
├── v2-150708.png
├── v2-150709.png
├── v2-150710.png
├── v2-150711.png
├── v2-150712.png
```

Some example images:

![symbol_id = XXX](v2-00151.png?raw=true "") 
![symbol_id = XXX](v2-01593.png?raw=true "") 
![symbol_id = XXX](v2-09067.png?raw=true "")
![symbol_id = XXX](v2-15496.png?raw=true "") 
![symbol_id = XXX](v2-16263.png?raw=true "") 
![symbol_id = XXX](v2-16808.png?raw=true "") 


symbols.csv format:
```csv
symbol_id	latex	training_samples	test_samples
31	A	137	22
32	B	53	8
33	C	120	14
.
.
.
81	\pi	1374	159
82	\alpha	2341	260
87	\beta	1018	113
88	\sum	3060	340
89	\sigma	1010	113

268	\checkmark	786	89
269	\circledR	106	13
508	\mathsection	114	13
510	\amalg	164	20

```

