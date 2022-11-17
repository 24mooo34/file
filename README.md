<memo>

★ssmのCLIコマンド
#パラメーターの上書き
aws ssm put-parameter --name '/db/password' --type SecureString --value 'ModifiedStrongPassword!' --overwrite

★RDSのCLIコマンド
#パスワードの変更
aws rds modify-db-instance --db-instance-identifier 'shimo-tf-db' --master-user-password 'NewMasterPassword!'

★Githubトークン
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
