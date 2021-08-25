VERSION --use-copy-include-patterns --for-in 0.5

FROM alpine

compile:
    LOCALLY
    FOR f IN $(find . -type f)
        SAVE ARTIFACT $f
    END
