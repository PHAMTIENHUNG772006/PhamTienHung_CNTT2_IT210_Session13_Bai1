Phân thích :

Tại sao thiếu hibernate.dialect lại khiến Hibernate không thể khởi động?

- Do nếu không có dialect thì hibernate không thể nhận dạng được hệ quản trị csdl nào để tiến hành khởi tạo do đó hibernate không thể khởi dộng

Thuộc tính nào giúp Hibernate tự động tạo bảng (medicines, prescriptions) từ Java Class?

- Thành phần giúp hibernate tạo ra các table trong csdl là setPackageToScan giúp quét các class trong package có Anotation @Entity để tạo bảng