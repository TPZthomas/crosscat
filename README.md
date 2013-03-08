tabular-predDB
==============

tabular predictive database

Running server
---------------------------
    > cd /path/to/tabular-predDB
    > make cython
    > cd /path/to/tabular-predDB/jsonrpc_http
    > # capture stdout, stderr separately
    > python server_jsonrpc.py >server_jsonrpc.out 2>server_jsonrpc.err &
    > # test with 'python stub_client_jsonrpc.py'

Running tests
---------------------------
    > cd /path/to/tabular-predDB
    > # capture stdout, stderr separately
    > make runtests >tests.out 2>tests.err

Building local binary
-------------------------------------------------
    > cd /path/to/tabular-predDB
    > make bin

