add_executable(benchmark_tcp_asio_client client.cpp)
target_link_libraries(benchmark_tcp_asio_client boost_system boost_thread pthread)

add_executable(benchmark_tcp_asio_server server.cpp)
target_link_libraries(benchmark_tcp_asio_server boost_system boost_thread pthread)
