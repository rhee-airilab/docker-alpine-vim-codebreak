# Usage

    $ docker build -t vim-codebreak .
    $ alias vim8='docker run -ti --rm -v $(pwd):$(pwd) -v /data:/data -w $(pwd) --entrypoint vim vim-codebreak'
    $ vim8 <your_target_file_to_break> -c VimGameCodeBreak

