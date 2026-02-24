FROM golang:latest

RUN <<EOR
	go install github.com/JohannesKaufmann/html-to-markdown/v2/cli/html2markdown@latest
EOR

CMD bash -c "curl -o - -sSL 'https://fr.wikipedia.org/wiki/Sp%C3%A9cial:Page_au_hasard' | html2markdown"
