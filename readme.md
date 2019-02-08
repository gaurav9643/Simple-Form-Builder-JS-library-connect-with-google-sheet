# Simple Form Builder JS library (Connect with Google Sheet)

Hi friends, You can add any forms(login,registration,contact us) to your website using the js library in few simple steps. Also you can connect your forms with server using the XMLHttpRequest. Also i'll guide you to connect your form with google excel sheet to store your form data.

## Features

- You can add forms like:- Registration, Login, Contact Us etc.
- Connect your form with Rest Api using XMLHttpRequest.
- Also you can connect your form with @Google Sheet

## Getting Started

These instructions will help you to use the library in your 'Web Projects'. Also help you to connect your forms with backed or googel sheet.

## How to use

### Add Library
```
<script src="lib.js"></script>
```

### Initialize Library

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <script src="js/lib.js"></script>
    <title>Title</title>
</head>
<body>
    <div id="formBuilder"></div>
    <script>
      new FormBuilder({
          selector:'formBuilder'
      });
    </script>
</body>
</html>
```


### Options

| Name  | Type | Default | Description |
| ----  | :---:  | :---:  |  :---:  |
| selector | String  | -   | Content Cell  |
| formClass | String  | form-builder  | Content Cell  |
| wrapperClass | String  | wrapper-form-builder  | Content Cell  |
| apiUrl | String  | http://dummy.restapiexample.com/api/v1/create  | Content Cell  |
| customFields | Boolean  | fasle  | Content Cell  |
| btnText | String  | Save  | Content Cell  |
| fields | Content Cell  | First Name, Last Name, Email  | Content Cell  |
| method | String  | GET  | Content Cell  |
| customCSS | Boolean  | true  | Content Cell  |
| success | Function  | -  | Content Cell  |
| error | Function  | -  | Content Cell  |
| notification | Boolean  | true  | Content Cell  |
| preloader | Boolean  | true  | Content Cell  |

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc

