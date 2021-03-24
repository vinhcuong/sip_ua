## NOTE

`grammar_parser.dart` is generated from `grammar.peg` using the [peg](https://github.com/cloudwebrtc/peg) tool.
Since the peg tool does not support `dart 2.x`, you need to use `dart 1.24.3`.

# Generate steps:
- Install `Dart 1.24.3`.

  `brew install dart@1`

  `export PATH="/usr/local/opt/dart@1/bin:$PATH"`

- Clone the peg tool and `pub get`.

  `cd tools`

  `git clone https://github.com/cloudwebrtc/peg`

  `cd peg`

  `pub get`

- Generate grammar parser

  `./tools/generate_grammar.sh`