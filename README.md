# CNVL_LAPLC

Convolution Laplacian filter on VHDL. 3x3 convolution kernel. 8 direction Laplacian filter.

## port

| name      | inout | P/N  | description                    |
| --------- | ----- | ---- | ------------------------------ |
| CLK       | I     | P    | System clock                   |
| nRST      | I     | N    | System reset                   |
| WR        | I     | P    | Raw data input enable          |
| RD        | O     | P    | Convolution data output timing |
| WDAT[7:0] | I     | P    | Raw data                       |
| RDAT[7:0] | O     | P    | Convolution data               |



# License

MIT License

# Author

[toms74209200](<https://github.com/toms74209200>)