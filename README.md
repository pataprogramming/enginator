# enginator

This is a proxy client to enable extended preset management in Artemis SBS.
The regular Artemis engineering client only provides ten preset slots. The
obsessive Engineer, however, may wish to maintain a much larger array of
energy and cooling configurations.

Please note that enginator is under development, and is not yet ready for
public use.

## Usage

To compile this version of enginator, you will need to download the 2.4.0
version of ArtClient lib and install the JAR into Leiningen's local Maven
repository.

  https://github.com/rjwut/ArtClientLib/releases/tag/v2.4.0

The [localrepo plugin](https://github.com/kumarshantanu/lein-localrepo) for
Leiningen is the best way to perform this installation, once the JAR is
downloaded:

```
% lein localrepo install artclientlib-2.4.0-jar rjwut/artclientlib 2.4.0
```

## License

Copyright © 2015 Paul L. Snyder

(License pending clarification of the license under which ArtClientLib
has been released)
