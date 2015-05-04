mimerl
=====

library to handle mimetypes

Build
-----

    $ make

Example of usage:
-----------------

    1> mimerl:extension(<<"c">>).
    <<"text/x-c">>
    2> mimerl:filename(<<"test.cpp">>).
    <<"text/x-c">>
    3> mimerl:mime_to_exts(<<"text/plain">>).
    [<<"txt">>,<<"text">>,<<"conf">>,<<"def">>,<<"list">>,
     <<"log">>,<<"in">>]
