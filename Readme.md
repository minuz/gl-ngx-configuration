# Jane - An Open Api (formerly Swagger) Client Generator

Jane is an [Open Api](https://www.openapis.org/) client generator. 
It uses templates written in handlebars to generate a client code base in various languages.

The initial release is focused on providing a strong support of csharp/netstandard1.3 
and typescript. 

# Documentation

Documentation is maintained in this repository [wiki](https://github.com/geeklearningio/gl-swagger-generator/wiki)

# Integration

Jane will have a CLI interface but is meant to be integrated in build pipeline such as gulp. 
A gulp plugin acting as a wrapper for Jane is [already available](https://github.com/geeklearningio/gulp-swagger-generator/tree/develop).
Please check the [wiki](https://github.com/geeklearningio/gl-swagger-generator/wiki) for guidance.

# Extensibility

One purpose of this generator is to allow you to write or customize templates if needed. Please check the wiki for more information.

