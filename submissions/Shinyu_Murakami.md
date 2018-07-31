---
layout: submissions
---

# Shinyu Murakami: Position Paper


- What's CSS typesetting
    - Print formatting of publications via CSS
    - There are dedicated softwares for CSS typesetting
    - Some of them use Web browser rendering engine, enhanced with JavaScript

- Many books are already made with CSS typesetting
    - Technical books
    - Trade books
    - Manuals and catalogs
    - Academic journals

- Various CSS typesetting engines
    - Proprietary softwares
        - [Prince](http://www.princexml.com/)
        - [PDFreactor](http://www.realobjects.com/products/pdfreactor/)
        - [Copper PDF](http://copper-pdf.com/)
        - [Antenna House Formatter](http://www.antenna.co.jp/AHF/)
        - [VersaType Converter](https://trim-marks.com/)
    - Open source softwares
        - [wkhtmltopdf](https://wkhtmltopdf.org/)
        - [WeasyPrint](https://weasyprint.org/)
        - [Vivliostyle](https://vivliostyle.org/)
        - [Paged.js](https://gitlab.pagedmedia.org/tools/pagedjs)

- Common problems on CSS typesetting
    - CSS typesetting engines implement different draft CSS page layout spec and they are not very compatible
    - Standardization of CSS page layout specs, such as:
        - Generated content for paged media
        - Page floats
        - Page templates
    - See also [Current Status of Japanese Typography Using Web Technologies](https://www.w3.org/Submission/2017/SUBM-CSJTUWT-20170102/)

- Web browser based CSS typesetting, such as Vivliostyle
    - Advantages:
        - Can use Web browser capabilities and standards support
        - Pagination on the Web, with print support
        - Responsive or adaptive page design is possible
        - Houdini APIs can be expected as a basis of making next generation CSS typesetting
    - Problems: Web browser's print/PDF output support is still poor and needs massive improvement
        - Problems on font embedding to PDF
        - Limited to RGB color
        - Subpixel rendering problem
        - Cannot generate standard-compliant PDFs such as PDF/X, PDF/A or PDF/UA

- Pagination on Web needs to be standardized
    - Scroll vs. pagination should be a user preference
    - In pagination mode, same page layout spec as printing should be available
    - CSS typesetting quality improvement brings about Web layout quality and readability improvement


Shinyu Murakami    
project leader at Vivliostyle.org

