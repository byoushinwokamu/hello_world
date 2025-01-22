add_executable(
	main
	main.c
	src/hello.c
)

target_include_directories(
	main
	PUBLIC inc
)
