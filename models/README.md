# Using Meta's Llama 7b model

### Option 1: 
1. Clone the [llama.cpp repository](https://github.com/ggerganov/llama.cpp/tree/master)https://github.com/ggerganov/llama.cpp/tree/master
2. Drag and drop the 7B file in this repository into the `/models` directory of the cloned llama.cpp repository
3. You can now execute your prompts using this model e.g. `./main -m ./models/7B/ggml-model-q4_0.bin --interactive -r "User:" -s 10 -f prompts/wikibot.txt --temp 0.8`

### Option 2: 
1.	Register for and download the llama2-7B model from Meta’s website. For more details on how to do so, refer to the official llama repository
2.	Clone the llama.cpp repository if you are running on Apple Silicon. If you are on Windows, you should be able to use the llama repository straight.
3.	Quantise the llama2-7B model into a 4-bit version to ensure it is compatible with your CPU. Command: `./quantize ./models/7B/ggml-model-f16.bin ./models/7B/ggml-model-q4_0.bin q4_0`. Note that your directory/names may differ
