build:
	mkdir -p functions
	go get ./...
	go build -ldflags "-X main.TELEGRAM_BOT_TOKEN=${TELEGRAM_BOT_TOKEN}" -o functions/echo ./...
