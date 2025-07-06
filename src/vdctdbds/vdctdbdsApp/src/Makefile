TOP=../..

# this creates a dbd file containing all the dbd files we want to use in VisualDCT
# you need to include DBD files that define new record types, but as vdct also checks the
# DTYP is valid you may want to include drivers too

include $(TOP)/configure/CONFIG

DBD += vdctdbds.dbd

vdctdbds_DBD += base.dbd
vdctdbds_DBD += asyn.dbd
vdctdbds_DBD += calcSupport.dbd
vdctdbds_DBD += busySupport.dbd
vdctdbds_DBD += motorSupport.dbd
vdctdbds_DBD += cvtRecord.dbd
vdctdbds_DBD += stdSupport.dbd
vdctdbds_DBD += sscanSupport.dbd
vdctdbds_DBD += stream.dbd

include $(TOP)/configure/RULES
#----------------------------------------
#  ADD RULES AFTER THIS LINE

