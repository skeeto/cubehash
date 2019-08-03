# CubeHash for Go

    go get github.com/skeeto/cubehash

Package cubehash implements djb's [CubeHash][spec] cryptographic hash
function, specifically the recommended CubeHash16+16/32+32–512 variant.
It's about 20x slower than the sha512 package, so more work needs to be
done optimizing this package.

[spec]: http://cubehash.cr.yp.to/
