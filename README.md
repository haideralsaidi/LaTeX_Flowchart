# LaTeX_Flowchart

LaTeX style file for flowchart symbols

File name: flowchartdef.sty

This file defines the styles for flowchart elements using TikZ.

Author: [Haider Al-Saidi]

Date: [2026-06]

Usage: Include this file in your LaTeX document with \usepackage{flowchartdef}

Example usage:

    \documentclass{article}
  
    \usepackage{tikz}
  
    \usepackage{flowchartdef}
  
    \begin{document}
  
    \begin{tikzpicture}[node distance=2cm, scale=1.0, every node/.style={transform shape} ]
  
        % Your flowchart code here
      
    \end{tikzpicture}
  
    \end{document}
  
Note: Adjust the styles and colors as needed for your specific flowchart design.

Define TikZ styles for flowchart elements

This file should be saved as flowchartdef.sty and included in your LaTeX document.
