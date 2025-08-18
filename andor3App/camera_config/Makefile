TOP=../..
include $(TOP)/configure/CONFIG
#----------------------------------------
#  ADD MACRO DEFINITIONS AFTER THIS LINE

#----------------------------------------------------
# Create and install (or just install)
# databases, templates, substitutions like this

MODELS = $(wildcard ../*.env)
DB_INSTALLS += $(MODELS)
DB_INSTALLS += $(subst .env,.template,$(MODELS))

#----------------------------------------------------
# If <anyname>.db template is not named <anyname>*.template add
# <anyname>_template = <templatename>

include $(TOP)/configure/RULES
#----------------------------------------
#  ADD RULES AFTER THIS LINE

