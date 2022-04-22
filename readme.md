### mkdir '폴더명'
새로운 폴더 생성
### cd '폴더명'
폴더로 이동
### ls
현재위치 확인
### vi
새로운 파일생성
### i
작업가능
###git add ' '.
입력 (장바구니담기) 스테이징함
###git commit -m "[32기 임종혁 변경내용입력]"
commit할 결과의 제목
###git push origin feature/jonghyeok(브렌치명)
gitpush 한다.(github에 올리기)
###작업내용
```
const even = () => {
  let nums = [];
  for (let i=1; i <= 50; i++) {
    if (i % 2 === 0) {
      nums.push(i);
    }
  }
  return nums;
}
console.log(even());
