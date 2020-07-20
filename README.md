# 서론
 
이 프로젝트는 2018년 창원대학교 고급자료구조의 마지막 과제인 BPlusTree의 구현입니다.

This project is 'Implement B plus tree with Java', the last assignment of Advanced Data Structure of Changwon National Univ.

# 본론

내용물 안에 한국어로 된 기사나 컬럼이 약 7만 2천여개가 존재합니다. 이를 모두 토큰화시켜 저장한 후, 어떤 파일에서 몇 번의 단어 빈도 수를 체크하여 데이터베이스화 합니다. 이를 BPlusTree로 구현합니다.

There're 72000s txt files with Korean news. This program uses tokenizer, save in the B plus tree(memory), based on frequency. This process can consume time about 7-10 mins.

# 결론

Height는 약 18정도가 나오고 결과의 출력은 0.5초 내에 가능합니다.

This tree has 18 height, you can get result(like How many words on files?) on under 500ms.
