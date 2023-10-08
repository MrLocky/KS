FROM dart:stable AS build

LABEL version = "1.0.1"

WORKDIR /testdir/dart

COPY . /testdir/dart/

CMD [ "dart" , "calc.dart" ]