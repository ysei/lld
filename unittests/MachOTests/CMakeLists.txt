
add_lld_unittest(lldMachOTests
  MachONormalizedFileBinaryReaderTests.cpp
  MachONormalizedFileBinaryWriterTests.cpp
  MachONormalizedFileToAtomsTests.cpp
  MachONormalizedFileYAMLTests.cpp
  )

target_link_libraries(lldMachOTests
  lldMachO
  lldYAML
  )
