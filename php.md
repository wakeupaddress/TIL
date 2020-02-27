```

if (!preg_match('/\A[a-zA-Z0-9]+\z/', $_POST['password'])) {
  throw new \MyApp\Exception\InvalidPassword();
}



```

if()は()がtrueでなければ処理は実行されない

上のコードは !false でtrueなのでifの処理が実行される

