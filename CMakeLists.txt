cmake_minimum_required(VERSION 3.0)

include(tacklelib/Project)

project("xz_lzma")

set(PROJECT_LIB_NAME xz_lzma)

tkl_check_var(REQUIRED PATH ARC_XZ_UTILS_ROOT)


find_library(XZ_LZMA_LIBRARY NAMES liblzma ${ARC_XZ_UTILS_ROOT}/lib)
