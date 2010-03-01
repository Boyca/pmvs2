cmake_minimum_required(VERSION 2.6)
project(pmvs2)

set(pmvs_SRCS detectFeatures.cc detector.cc dog.cc expand.cc filter.cc findMatch.cc harris.cc optim.cc option.cc patch.cc patchOrganizerS.cc point.cc seed.cc)
add_library(pmvs SHARED ${pmvs_SRCS})
