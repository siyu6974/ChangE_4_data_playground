# ChangE_4_data_playground

## Preq

- pds4_tools
- colour-demosaicing
- Pillow

All available on pip

## Usage

Download Chang'E 4 data from http://moon.bao.ac.cn and put them in `PCAM` and `TCAM` folder respectively.

The `first_glance` notebook gives you a preview of the data. You can use the `export` notebook to batch convert PDS files to png.

## Functions
- read pds4 image
- debayer
- 2% linear stretch
- export to png
