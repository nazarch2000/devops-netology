# Ryzhenko
# devops-netology
# В файлe .gitignore будут игнорироваться такие файлы как:
*.tfstate 
# Это файлы состояния Terraform инфраструктуры. Они содержат конфиденциальную информацию, такую как пароли и ключи API, поэтому они не должны быть включены в репозиторий.


*.tfvars
*.tfvars.json 
# Исключить все файлы .tfvars, которые могут содержать конфиденциальные данные, такие как пароль, закрытые ключи и другие секреты.


override.tf
override.tf.json
*_override.tf
*_override.tf.json
# Игнорировать файлы переопределения, так как они обычно используются для локального переопределения ресурсов и т.д.


.terraformrc
terraform.rc
# Под разные проекты могут использоваться разные настройки.
# Если файл .terraformrc является частью общей конфигурации проекта и требуется, чтобы во всех проектах использовались одинаковые настройки Terraform, 
# то его можно добавить в репозиторий. В этом случае обязательно нужно удалить из файла .terraformrc любую конфиденциальную информацию, такую как пароли и ключи API.


# Это только некоторые файлы и каталоги, которые могут быть добавлены в .gitignore при работе с Terraform. 
# В зависимости от проекта могут быть и другие файлы, которые также следует исключить из репозитория.
