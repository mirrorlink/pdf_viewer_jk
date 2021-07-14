this fork basically add the option "withZoom" in order to remove the zoomablewidget from the PDFPage widget that may be troublesome depending on the widget hierarchy

defaults to true on PDFViewer
defaults to false everywhere else (like in the PDFDocument get method)
