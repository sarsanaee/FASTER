set(BENCHMARK_HEADERS
  file.h
)

set(BENCHMARK_SOURCES
)

ADD_FASTER_BENCHMARK(faster-benchmark)


target_include_directories(benchmark PRIVATE /home/alireza/FASTER/cc/third_party/HdrHistogram_c/include/hdr)

add_executable(process_ycsb process_ycsb.cc)

