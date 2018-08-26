Crazy command to build a static binary, run in jctl folder:

CGO_ENABLED=0 GOOS=linux go build -a -installsuffix cgo -o ../../../../bin/jctl .
