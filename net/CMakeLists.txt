cmake_minimum_required(VERSION 3.0)

add_library(net SHARED ClientSocket.cpp ConnectedSocket.cpp InetAddress.cpp ServerSocket.cpp Socket.cpp SocketMultiplexer.cpp TimerManager.cpp SocketReadManager.cpp SocketWriteManager.cpp SocketExceptionManager.cpp Request.cpp Response.cpp AcceptedSocket.cpp Descriptor.cpp Timer.cpp FileReader.cpp)

target_include_directories (net PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
