# 42 Berlin

Projects from the [42 Berlin](https://www.42berlin.de/de) coding school, written in C following the 42 Norm.

## Piscine
Exercises from the C Piscine: string functions (`ft_strcpy`, `ft_strcmp`, `ft_strstr`, ...).
- Status: partial (C02 and most of C03)

## libft
My own C library. 23 libc functions re-implemented (`ft_strlen`, `ft_memmove`, `ft_atoi`, ...), 11 extra utilities (`ft_split`, `ft_itoa`, `ft_strjoin`, ...) and a linked-list functions (`ft_lst*`).
- Status: complete, including the bonus part

## ft_printf
Re-implementation of `printf` using variadic arguments. Supports `%c %s %p %d %i %u %x %X %%`.
- Status: complete (mandatory part)

## get_next_line
Reads a file descriptor one line at a time, using a static buffer and a configurable `BUFFER_SIZE`.
- Status: complete (mandatory part)

## What I learned
C programming languages, pointers and manual memory management (`malloc`/`free`), file descriptors and `read`, variadic functions, static variables, Makefiles and static libraries.
 
---

(Korean ver.)

# 42 Berlin

코딩 학교 [42 Berlin](https://www.42berlin.de/de) 에서 42 Norm에 맞춰 C로 작성한 프로젝트들입니다.

## Piscine
C Piscine 과제 중 문자열 함수들(`ft_strcpy`, `ft_strcmp`, `ft_strstr` 등)입니다.
- 상태: 일부 완료 (C02 전체, C03 대부분)

## libft

직접 만든 C 라이브러리 입니다. libc 함수 23개를 직접 구현했고(`ft_strlen`, `ft_memmove`, `ft_atoi` 등), 추가 함수 11개(`ft_split`, `ft_itoa`, `ft_strjoin` 등)와 연결 리스트 함수(`ft_lst*`)를 만들었습니다.
- 상태: 보너스 포함 완성

## ft_printf
가변 인자를 사용해 `printf`를 다시 구현했습니다. `%c %s %p %d %i %u %x %X %%`를 지원합니다.
- 상태: 필수 부분 완성

## get_next_line
정적 변수와 `BUFFER_SIZE` 설정을 사용해, 파일 디스크립터에서 한 줄씩 읽어 옵니다.
- 상태: 필수 부분 완성

## 배운 것
C 프로그래밍 언어와 포인터, 수동 메모리 관리 (`malloc`/`free`), 파일 디스크립터와 `read`, 가변 인자 함수, 정적 변수, Makefile과 정적 라이브러리 등을 배울 수 있었습니다.
