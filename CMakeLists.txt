add_executable(
	main
	main.c
	src/hello.c
    src/bonjour.c
)

target_include_directories(
	main
	PUBLIC inc
)
