add_llvm_library(LLVMARMDesc
  ARMAsmBackend.cpp
  ARMELFObjectWriter.cpp
  ARMELFObjectWriter.cpp
  ARMELFStreamer.cpp
  ARMMachObjectWriter.cpp
  ARMMachORelocationInfo.cpp
  ARMMCAsmInfo.cpp
  ARMMCCodeEmitter.cpp
  ARMMCExpr.cpp
  ARMMCNaCl.cpp # LOCALMOD
  ARMMCNaClExpander.cpp # LOCALMOD
  ARMMCTargetDesc.cpp
  ARMTargetStreamer.cpp
  ARMUnwindOpAsm.cpp
  ARMWinCOFFObjectWriter.cpp
  ARMWinCOFFStreamer.cpp
  )
