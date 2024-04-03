# RingNull Template

## About This Template

I created this template for myself, to use in my videos and for my own needs. 

 This theme combines elements from the IIIT-Hyderabad, Statale and Focus themes with some custom additions. 

 Contributions:
 - Statale theme adapted by Srikar Sharma Sadhu (srikar.sadhu@research.iiit.ac.in) for IIIT-Hyderabad
 - Giorgio Marchetti (ciao@gio.im) for Statale presentations. 
 - Original template by Federico Zenith (federico.zenith@sintef.no)
 		derived from Håvard Berland's beamerthementnu class.
 - Focus theme by Pasquale Claudio Africa (2018) and Sebastian Friedl (2018).

# Features

- Four different color themes, which can be switched with an optional argument to the theme, `red`, `blue`, `purple` and `green`
- A footline that isn't just a number, but is instead a bar that fills from left to right. 
- Full and automatic bibliography support included in `\backmatter`
- A `headless` frame option to produce frames without title slides.
- Multiple `tcblistings` enviroments using minted to produce beautiful source code slides.
- An optional watermark. 

# Examples

<img src="https://github.com/RingNull/ringnull-latex-template/blob/media/Images/Title-red.jpg?raw=true " alt="Title Red" width="24%"/>
<img src="https://github.com/RingNull/ringnull-latex-template/blob/media/Images/Title-blue.jpg?raw=true " alt="Title Blue" width="24%"/>
<img src="https://github.com/RingNull/ringnull-latex-template/blob/media/Images/Title-purple.jpg?raw=true " alt="Title Purple" width="24%"/>
<img src="https://github.com/RingNull/ringnull-latex-template/blob/media/Images/Title-green.jpg?raw=true " alt="Title Green" width="24%"/>
<br>
<br>
<img src="https://github.com/RingNull/ringnull-latex-template/blob/media/Images/Blocks-red.jpg?raw=true " alt="Blocks Red" width="24%"/>
<img src="https://github.com/RingNull/ringnull-latex-template/blob/media/Images/Blocks-blue.jpg?raw=true " alt="Blocks Blue" width="24%"/>
<img src="https://github.com/RingNull/ringnull-latex-template/blob/media/Images/Blocks-purple.jpg?raw=true " alt="Blocks Purple" width="24%"/>
<img src="https://github.com/RingNull/ringnull-latex-template/blob/media/Images/Blocks-green.jpg?raw=true " alt="Blocks Green" width="24%"/>
<br>
<br>
<img src="https://github.com/RingNull/ringnull-latex-template/blob/media/Images/Pallets.jpg?raw=true " alt="Pallets" width="49%"/>
<img src="https://github.com/RingNull/ringnull-latex-template/blob/media/Images/Pallets-2.jpg?raw=true " alt="Pallets 2" width="49%"/>
<br>
<img src="https://github.com/RingNull/ringnull-latex-template/blob/media/Images/Columns.jpg?raw=true " alt="Columns" width="49%"/>
<img src="https://github.com/RingNull/ringnull-latex-template/blob/media/Images/Headless.jpg?raw=true " alt="Headless" width="49%"/>
<br>
<img src="https://github.com/RingNull/ringnull-latex-template/blob/media/Images/Listings.jpg?raw=true " alt="Listings" width="49%"/>
<img src="https://github.com/RingNull/ringnull-latex-template/blob/media/Images/Lists.jpg?raw=true " alt="Lists" width="49%"/>

# Building

This LaTeX template uses TikZ for the title, fontspec for custom fonts, biblatex/biuber for the bibliography. 

A basic compliation work flow would be: 

```
git clone https://github.com/RingNull/ringnull-latex-template
cd ringnull-latex-template
xelatex main
biber main
xelatex main
```

# License

This work is released under the GNU General Public License V3. See LICENSE for details. 