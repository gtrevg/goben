# goben
goben is a golang tool to measure TCP throughput between hotsts.

Install
=======

    go get github.com/udhos/goben
    go install github.com/udhos/goben/goben

Usage
=====

Start server:

    server$ ~/go/bin/goben

Start client:

    client$ ~/go/bin/goben -hosts 1.1.1.1 ;# 1.1.1.1 is server's address
