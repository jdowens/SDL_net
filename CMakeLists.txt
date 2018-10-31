project(SDL_net)

include_directories(../SDL/include)

add_library(SDL2_net SDL_net.h
                     SDLnetsys.h
                     SDLnet.c
                     SDLnetTCP.c
                     SDLnetUDP.c
                     SDLnetselect.c) 
