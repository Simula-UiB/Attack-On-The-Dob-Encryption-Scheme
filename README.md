<h1 align="center">Attack on the Dob Encryption Scheme</h1>
<p align="center">
    <a href="https://github.com/Simula-UiB/Attack-On-The-Dob-Encryption-Scheme/blob/master/AUTHORS"><img src="https://img.shields.io/badge/authors-SimulaUIB-orange.svg"></a>
    <a href="https://github.com/Simula-UiB/Attack-On-The-Dob-Encryption-Scheme/blob/master/LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue.svg"></a>
</p>

Contains Magma scripts for generating the public key of the Dob encryption scheme, as well as an implementation of the attack on this construction.

## License

This repository is licensed under the MIT License.

* MIT license ([LICENSE](LICENSE) or http://opensource.org/licenses/MIT)


## Overview

The first script generates the public key of a Dob encryption scheme with various parameter choices. A Gröbner basis can be computed directly from this. The second script recovers the system \mathcal{G}, as described in Section 6.2 of the article. The third script recovers a basis for the oplus modification, v_1*,...,v_k*, as described in Section 6.3 of the article.

## Restrictions

Script two and three requires the previous script(s) in order to run. The attack has only been implemented with the use of three variable sets, W_1, W_2 and W_3, in the gluing process. Furthermore, only the cases k = 0 and k > 3, where k is the number of linear forms in the oplus modification, have been implemented.
