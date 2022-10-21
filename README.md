# learning_go
https://dev.to/augusto_queirantes/learning-go-creating-the-environment-using-docker-part-1-id2


git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/MathRober/learning_go.git
git push -u origin main
git config -l
git remote set-url origin https://MathRober@github.com/MathRober/learning_go.git
git remote set-url origin https://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@github.com/MathRober/learning_go.git


docker-compose up -d 
docker exec -it learning_go sh

go mod init github.com/mathrober/learning_go
go get -u github.com/gin-gonic/gin
go run .
