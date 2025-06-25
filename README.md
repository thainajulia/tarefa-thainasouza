# tarefa-thainasouza
Loja PHP - Sistema Completo com Registo, Login, Carrinho e Pagamento via PayPal
24198_Loja/

<?php
const EMAIL_FROM = 'seuemail@sapo.pt';
const EMAIL_NAME = 'Loja PHP';
const EMAIL_PASS = 'sua_password_app';
const PAYPAL_CLIENT_ID = 'SEU_CLIENT_ID_SANDBOX';
const PAYPAL_SECRET = 'SEU_SECRET_SANDBOX';
const PAYPAL_BASE_URL = 'https://api-m.sandbox.paypal.com'; // use api-m.paypal.com para produção

├── api/
│   ├── admin/
│   │   ├── insert_product.php
│   │   ├── edit_product.php
│   │   └── delete_product.php
│   ├── PHPMailer/
│   ├── add_to_cart.php
│   ├── auth.php
│   ├── db.php
│   ├── delete_cart.php
│   ├── email.php
│   ├── secrets.php ← (você deve criar este ficheiro)
│   └── update_cart.php
├── views/
│   ├── areaadmin.php
│   ├── ativarconta.php
│   ├── cart.php
│   ├── finish.php
│   ├── login.php
│   ├── logout.php
│   └── registo.php
├── 24198_Loja.sql
└── index.php
