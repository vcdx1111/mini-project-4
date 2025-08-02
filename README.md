# mini-project-4
assembly로 구구단 출력 (NASM이 필요합니다!)

1. linux kernel 기준 (ubuntu)
2. 파일 다운로드 (txt)
3. txt 파일에 있는 코드를 ubuntu kernel에 들어가서 nano gugudan.asm
4. 코드 복붙하고 ctrl O하고 엔터치고 ctrl X로 나오기
5. 컴파일: nasm -f elf64 gugudan.asm -o gugudan.o
6. 링킹: ld   gugudan.o -o gugudan
7. 실행: ./gugudan
8. 숫자입력!

P.S. 어셈블리 어려워요 ㅠㅠ
