install:
	brew install finch

check:
	finch --version
	finch vm status

init:
	finch vm init

hello:
	finch run public.ecr.aws/finch/hello-finch:latest

build:
	finch build --tag hello-finch .

images:
	finch image list
