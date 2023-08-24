build:
	ghc main.hs

clean:
	rm main main.hi main.o

run:
	./main

bash:
	docker run -v $(pwd):/opt/main -w /opt/main -it haskell bash
