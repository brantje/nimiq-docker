
Just execute the nimiq process.   
One can customize the created container easily
to one's needs by mount your own nimiq.conf to the container at `/etc/nimiq/nimiq.conf`.   
Then you can just create the container like (assuming the config is in the current working directory).   
`docker run nimiq/nodejs-client -v $(pwd)/nimiq.conf:/etc/nimiq/nimiq.conf --config=/etc/nimiq/nimiq.conf`
