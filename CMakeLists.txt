cmake_minimum_required(VERSION 2.8)

INSTALL (FILES regexes.yaml DESTINATION usr/share/uap-core/)
INSTALL (DIRECTORY test_resources DESTINATION usr/share/uap-core/)
INSTALL (DIRECTORY tests DESTINATION usr/share/uap-core/)
INSTALL (DIRECTORY docs DESTINATION usr/share/uap-core/)
