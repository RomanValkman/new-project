# Опис Git

# Список команд для створення файлу та репозиторію

mkdir new-project

cd new-project

git init new-project

touch README.md

h1=$(git hash-object -w README.md)
git update-index --add --cacheinfo 100644 $h1 README.md
t1=$(git write-tree)
echo -n "init"|git commit-tree $t1


уувулцрцулвруцлвр
