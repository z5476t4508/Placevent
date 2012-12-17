Placevent
=========

Placevent - 3D-RISM-based solvent and ion placement softwareCreated by Daniel Sindhikara, sindhikara@gmail.com
Placevent
This program is designed to automatically place explicit solvent atoms/ions based
on 3D-RISM data. The 3D-RISM correlations should be in a DX file

The details of the algorithm are described in: 
Placevent: An algorithm for prediction of explicit solvent atom distribution -- Awpplication to HIV-1 protease and F-ATP synthase 
Daniel J. Sindhikara, Norio Yoshida, Fumio Hirata
http://dansindhikara.com/Software/Entries/2012/6/22_Placevent_New.html

If you have Numpy, this package should work out of the box. Please contact me if you have problems.
This package requires Numpy.

There is a degree of uncertainty in the placement due to the conversion of continuous distribution to
a discrete one. The atoms are printed in PDB format with the beta term reflecting the uncertainty.

//    Copyright (C) 2012 Daniel J. Sindhikara
//
//    This program is free software: you can redistribute it and/or modify
//    it under the terms of the GNU General Public License as published by
//    the Free Software Foundation, either version 3 of the License, or
//    (at your option) any later version.
//
//    This program is distributed in the hope that it will be useful,
//    but WITHOUT ANY WARRANTY; without even the implied warranty of
//    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
//    GNU General Public License for more details.
//
//    You should have received a copy of the GNU General Public License
//    along with this program.  If not, see <http://www.gnu.org/licenses/>.
