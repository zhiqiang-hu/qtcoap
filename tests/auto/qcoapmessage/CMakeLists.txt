# Generated from qcoapmessage.pro.

#####################################################################
## qcoapmessage Test:
#####################################################################

qt_add_test(qcoapmessage
    SOURCES
        tst_qcoapmessage.cpp
    PUBLIC_LIBRARIES
        Qt::Coap
        Qt::Network
)
