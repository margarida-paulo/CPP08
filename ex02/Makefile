NAME = ex02

CPP = c++

FLAGS = -Wall -Wextra -Werror -std=c++98 -g

FILES = main.cpp

HEADERS = MutantStack.hpp

all: ${NAME}

${NAME}: ${FILES} ${HEADERS}
	${CPP} ${FLAGS} ${FILES} -o ${NAME}

clean:

fclean:
	rm ${NAME}

re:
	make fclean
	make