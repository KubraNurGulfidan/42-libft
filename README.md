### Libft

## Proje Hakkında (TR)
Bu proje, 42 eğitim programı kapsamında C standart kütüphanesindeki (libc) fonksiyonları en baştan yazarak kendi kütüphanemi oluşturduğum projedir. Projenin amacı, veri yapılarını, bellek yönetimini ve C dilinin temel mantığını en alt seviyede kavramaktır.

## Teknik İçerik
- **Standart Libc Fonksiyonları:** isalpha, isdigit, isalnum, isascii, isprint, strlen, memset, bzero, memcpy, memmove, strlcpy, strlcat, toupper, tolower, strchr, strrchr, strncmp, memchr, memcmp, strnstr, atoi, calloc, strdup
- **Ek Fonksiyonlar:** ft_substr, ft_strjoin, ft_split, ft_itoa, ft_strtrim, ft_itoa, ft_strmapi, ft_striteri, ft_putchar_fd, ft_putstr_fd, ft_putendl_fd, ft_putnbr_fd string ve veri işleme araçları.
- **Bonus (Bağlı Listeler):** Linked list yönetimi için ft_lstnew, ft_lstadd_back, ft_lstmap fonksiyonlar.

## Kullanım
1.  Kütüphaneyi derlemek ve `libft.a` dosyasını oluşturmak için:
  ```bash
  make
2. Bonus fonksiyonları dahil etmek için:
  ```bash
  make bonus

## About the Project (EN)
This project is the foundational project of 42 school, where I re-implemented standard C library (libc) functions to create my own library. The goal is to understand data structures, memory management, and the core logic of C at a low level.

## Technical Contents
- **Standard Libc Functions**: Re-implementation of core functions like strlen, memcpy, strdup, atoi, etc.
- **Additional Functions**: String and data processing utilities such as ft_substr, ft_strjoin, ft_split, ft_itoa.
- **Bonus (Linked Lists)**: Functions for managing linked lists like ft_lstnew, ft_lstadd_back, ft_lstmap.

## Usage
1. To compile the library and generate the libft.a file:
  ```bash
  make
2. To include bonus functions:
  ```bash
  make bonus
