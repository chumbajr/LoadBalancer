# GO LOAD HTTP BALANCER
        This is a simple golang http proxy load balancer


## USAGE:
        go run main.go -servers=<server1 URL>,<sever2 URL> -port=<load balancer port>
        
        The Default Load Balancer Port is 4000. 
        You can change port number with -port=<Port> option
        
    Example:
        go run main.go -servers=http://localhost:8000,http://localhost:8001 -port=4000        
