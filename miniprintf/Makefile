##
## EPITECH PROJECT, 2023
## makefile miniprintf
## File description:
## Makefile for miniprintd
##

SRC	=	mini_printf.c	\
		my_putchar.c	\
		my_put_nbr.c	\
		my_putstr.c	\
		my_strlen.c	\
		print_arg.c	\

OBJ	=	$(SRC:.c=.o)

NAME	=	libmini.a

all:	$(NAME)

$(NAME):	$(OBJ)
	ar rc $(NAME) $(OBJ)
	cp ./libmini.a ../lib/
	cp header.h ../include/mini_printf.h

clean:
	rm -f $(OBJ)

fclean:	clean
	rm -f $(NAME)
	rm -f ../lib/$(NAME)
	rm -f ../include/my_radar/mini_printf.h

re:	fclean all

.PHONY: all clear fclean re
