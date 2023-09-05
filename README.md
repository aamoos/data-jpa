# data-jpa

# 처음 h2 database 만드는방법
- 처음접속할때는 database가 없어서 접근이 안됨, 해당 url로 접속해서 database 파일을 만들어줌
- jdbc:h2:~/datajpa

![image](https://github.com/aamoos/data-jpa/assets/37327676/d9356761-8b8f-4ded-8cd3-371aa159f657)

# 만든 이후에 data base 접속방법
- 위에 방법대로 접속 하면 lock이 걸려 한명만 접근 가능, 맨 처음에 database 생성시 위 명령어로 접속하고, 이후에는 tcp로 접속함 (이방법은 여러명이 접속 가능)
- jdbc:h2:tcp://localhost/~/datajpa

![image](https://github.com/aamoos/data-jpa/assets/37327676/0aa2765e-431f-4bbd-a3d1-6a1d0a3566de)
