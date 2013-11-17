add_executable(d64bsp
analyze.c
blockmap.c
display.c
glbsp.c
level.c
main.c
node.c
reject.c
seg.c
system.c
util.c
wad.c
)

target_link_libraries(d64bsp m)
