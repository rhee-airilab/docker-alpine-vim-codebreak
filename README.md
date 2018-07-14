# Usage

    $ docker build -t vim-codebreak:0.1 .
    $ alias vim8='docker run -ti --rm -v $(pwd):$(pwd) -v /data:/data -w $(pwd) --entrypoint vim vim-codebreak:0.1'
    $ vim8 -c VimGameCodeBreak <your_target_file_to_break> 

