docker build -t alunde/theta_dev:latest .
docker run -ti -p 22:22 alunde/theta_dev:latest

~/.bashrc

PATH="/home/user/bin:$PATH"
export PATH

docker cp 47c07d3ba00a:/usr/bin/vim.basic .

