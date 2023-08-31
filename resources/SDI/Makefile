# Copyright 2009-2014 The MathWorks, Inc.

# When creating new catalogs, simply add them to L10N_XML_FILES below.
# Please do not add code to automatically find new catalogs.
#
# To make catalogs accessible from C++, add them to CXX_XML_FILES too.
#
# Please consult with I&A's I18n team before make any other modifications 
# to this file.  Use the i18n-help mailing list to reach us quickly.

COMPONENT := SDI_resources

# Message Catalog items that need to be available for JavaScripts
JS_XML_FILES := \
  en/sdi.xml \
  en/dialogs.xml \
  en/timeScope.xml \
  en/toolStrip.xml \
  en/sigAnalyzer.xml \
  en/toolStripSigAnalyzer.xml \
  en/dialogsSigAnalyzer.xml \
  en/labeler.xml \
  en/toolStripLabeler.xml \
  en/dialogsLabeler.xml \
  
# List of message catalogs which we expect to be translated
# Uncomment this list as we delete the xlate messages directory
L10N_XML_FILES := \
  en/sdi.xml \
  en/dialogs.xml \
  en/timeScope.xml \
  en/toolStrip.xml \
  en/sigAnalyzer.xml \
  en/toolStripSigAnalyzer.xml \
  en/dialogsSigAnalyzer.xml \
  en/labeler.xml \
  en/toolStripLabeler.xml \
  en/dialogsLabeler.xml \
  en/MatchesSignal.xml \
  en/SignalComparisonDiagnostic.xml \

# Generate C++ interfaces for a subset of our messages
CXX_XML_FILES := \
  en/sdi.xml \
  en/sigAnalyzer.xml \

include $(BUILD_HARNESS)/makerules/sandbox_root.mk
include $(SANDBOX_ROOT)/resources/internal/makerules/resource_component.mk

