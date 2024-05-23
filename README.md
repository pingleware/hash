# hash

Public repository of official program hashes to check binary integrity compatibility that provides a mechanism that prevents program binary alteration and throws an exception if the binary is altered, we can use a technique called checksum or hash verification. The idea is to generate a cryptographic hash (e.g., SHA-256) of the binary file at the time of its deployment and store this hash securely. At runtime, the program can recompute the hash of its binary and compare it to the stored hash. If they do not match, it indicates that the binary has been altered.

The build process inclludes creating a UUID that will contain the application hash and then create the hash and save to this repository automatically for example, through the **npm run build** command.

The following table for reference purposes ONLY.

| APPLICATION        | VERSION | FRAMEWORK | UUID                                 |
| ------------------ | ------- | --------- | ------------------------------------ |
| redeecash-interest | 1.1.2   | nodejs    | c7d32707-eb1e-599d-9a82-35ffade24a6a |
|forexgeneral-trader|1.1.2|nodejs|d7ca9e19-f103-50a8-96b9-7d909997b910|
|officesupplymanagement|1.0.2|nodejs|21648453-74a1-5e5e-b198-f46c69f2247d|
