# Go2Pydantic

It is an utility that reads from stdin a model in Go that has `json` struct tags and outputs an straightforward translation to a Pydantic model.

You can copy it to your `bin` directory, then use it like `echo 'go-model' | go2pydantic` and copy the output in your code.
