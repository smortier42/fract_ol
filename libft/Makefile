# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: smortier <marvin@42.fr>                    +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2017/11/08 17:05:13 by smortier          #+#    #+#              #
#    Updated: 2017/11/20 09:00:43 by smortier         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

SOURCE = ft_putchar.c \
		 ft_putstr.c  \
		 ft_putnbr.c  \
		 ft_strlen.c  \
		 ft_strdup.c  \
		 ft_strcmp.c  \
		 ft_strcpy.c  \
		 ft_strncpy.c \
		 ft_strcat.c  \
		 ft_strncat.c \
		 ft_memalloc.c\
		 ft_memset.c  \
		 ft_bzero.c   \
		 ft_memcpy.c  \
		 ft_memccpy.c \
		 ft_memmove.c \
		 ft_memchr.c  \
		 ft_memcmp.c  \
		 ft_strchr.c  \
		 ft_strrchr.c \
		 ft_strstr.c  \
		 ft_strnstr.c \
		 ft_strncmp.c \
		 ft_atoi.c    \
		 ft_isalpha.c \
		 ft_isdigit.c \
		 ft_isalnum.c \
		 ft_isascii.c \
		 ft_isprint.c \
		 ft_toupper.c \
		 ft_tolower.c \
		 ft_memdel.c  \
		 ft_strnew.c  \
		 ft_strdel.c  \
		 ft_strclr.c  \
		 ft_striter.c \
		 ft_striteri.c\
		 ft_strmap.c  \
		 ft_strmapi.c \
		 ft_strequ.c  \
		 ft_strnequ.c \
		 ft_strsub.c  \
		 ft_strjoin.c \
		 ft_strtrim.c \
		 ft_putendl.c \
		 ft_putchar_fd.c\
		 ft_putstr_fd.c \
		 ft_putendl_fd.c\
		 ft_putnbr_fd.c \
		 ft_itoa.c    \
		 ft_strclen.c \
		 ft_nbcwords.c\
		 ft_strsplit.c\
		 ft_strlcat.c \
		 ft_lstnew.c \
		 ft_lstdelone.c\
		 ft_lstdel.c  \
		 ft_lstadd.c  \
		 ft_lstiter.c \
		 ft_lstmap.c  \
		 ft_create_elem.c \
		 ft_lst_push_back.c \
		 ft_lst_size.c \
		 get_next_line.c

NAME = libft.a

OBJET = $(SOURCE:.c=.o)

INCS = -I.

all : $(NAME)

$(NAME) : $(OBJECT)
	@gcc -Wall -Werror -Wextra -c $(INCS) $(SOURCE)
	@ar rc $(NAME) $(OBJET)

clean :
	@rm -f $(OBJET)

fclean : clean
	@rm -f $(NAME)

re : fclean all
