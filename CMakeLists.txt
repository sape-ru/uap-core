cmake_minimum_required(VERSION 2.8)

INSTALL (FILES regexes.yaml DESTINATION share/uap-core/)
INSTALL (DIRECTORY test_resources DESTINATION share/uap-core/)
INSTALL (DIRECTORY tests DESTINATION share/uap-core/)
INSTALL (DIRECTORY docs DESTINATION share/uap-core/)
