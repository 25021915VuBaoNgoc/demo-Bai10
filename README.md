Không tồn tại version 9.9.9 của dependency logback-classic

maven-surefire-plugin version 2.12.4 -> version quá cũ k hỗ trợ JUnit 5 chỉ hỗ trợ IUnit 4

ci.yml, thiếu actions/checkout@v3 Github Actions runner là máy ảo trống -> source code ko đc copy vào runner -> k build đc 

tạo testNullType: khi cho type == null, null k thực hiện lệnh equals đc nên -> ném NullPointerException