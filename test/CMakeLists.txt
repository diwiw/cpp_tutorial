cmake_minimum_required(VERSION 3.16.3)

file(GLOB SRC_TEST_FILES
	"*.cpp"
)

add_executable(CPPTutorial-test
	${SRC_TEST_FILES}
)
