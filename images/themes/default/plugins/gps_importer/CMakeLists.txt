FILE(GLOB IMAGES *.png *.svg)

INSTALL (FILES ${IMAGES}
         DESTINATION ${QGIS_DATA_DIR}/themes/default/plugins/gps_importer)
