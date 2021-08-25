VERSION --use-copy-include-patterns --for-in 0.5

FROM alpine

source-files:
    LOCALLY
    FOR f IN $(find . -type f)
        SAVE ARTIFACT $f
    END

compile:
    COPY +source-files/* .
    FOR f IN $(find . -type f)
	RUN echo $f
    END
