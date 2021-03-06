## AES(Advanced Encription Standard)란?

기술이 발전함에 따라 DES 알고리즘은 짧은 키 길이로 인해 안전성을 보장할 수 없게 됩니다.  
3DES(Triple DES)와 같은 경우 지금까지도 안전하지만 구현 시 효율적이지 못하여, 미 국가 표준 기술연구소(NIST)에서는 새로운 블록 암호의 필요성을 제기하게 됩니다.  
그렇게 만들어진 것이 AES(Advanced Encryption Standard, 진보된 암호화 표준)입니다.  
AES는 공모전으로 새로운 알고리즘을 선발하였고 그 결과 리즈 멘(Rijmen)과 (Daemen)의 Rijndael 알고리즘이 AES로 선정되게 됩니다.

#### AES의 특징

가변 길이의 키와 블록 사용 가능
- 블록과 키 모두 128비트, 192비트, 256비트 중 선택할 수 있습니다.
- 128비트 블록과 키를 갖는 알고리즘이 AES의 표준화

|키 길이(bit)|라운드 수|
|------------|--------|
|128|10|
|192|12|
|256|14|
