# How to setup development environment

1. Clone the repo
2. Run `make init`
3. Setup external dependencies 

        AWS_PROFILE=... make init-external-deps
        
4. You are all set!

## Running locally

    # start local env
    make start
    
    # ... in case you would like to apply your code changes instantly
    make watch-and-rebuild
    
    # ... or maybe you want to rebuild app on demand
    make rebuild
    
    # ... check logs
    make tail-logs
    
    # stop local env
    make stop
    
 
## Running tests

    # run all tests
    make tests
    
    # run only unit tests
    make tests-unit
    
    # run only acceptance tests
    make tests-acceptance
