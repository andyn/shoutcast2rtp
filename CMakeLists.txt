# Shoutcast2rtp root CMakeList

# Dunno about the real requirements, 2.6 should suffice. The current
# version in Ubuntu LTS 10.04 repos is 2.8.
cmake_minimum_required (VERSION 2.6)

# Project name. Shoutcast2rtp shall suffice for now
project (ShoutcastToRtp)

# Main source tree
add_subdirectory(src)
