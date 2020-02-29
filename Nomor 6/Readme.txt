Cara Menjalankan nya :

1. Buka Xampp
2. Masuk Ke "phpmyadmin" (localhost)
3. klik Import 
4. klik "choose file"
5. Cari file "product.sql"
6. klik "Go"
7. klik database "product" -> klik "tb_cashier"
8. klik "sql"
9. copy perintah dibawah ini :
    SELECT tb_cashier.name_cashier, tb_product.name, tb_category.name_category, tb_product.price
    FROM tb_product
    JOIN tb_category ON (tb_category.id_category = tb_product.id_category)
    JOIN tb_cashier ON (tb_cashier.tb_cashier = tb_product.id_cashier)
10. Klik "Go"