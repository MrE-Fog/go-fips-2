## go-fips

Proof-Of-Concept for using golang and building a FIPS enabled application.


## Setup

See http://www.openssl.org/docs/fips/UserGuide-2.0.pdf
to set up an environment where fips mode can be enabled

## Building

```
go build .
```

and

```
go build -tags fips .
```

## Testing

```
go test .
```

and

```
go test -tags fips .
```

