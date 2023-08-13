## Objective

The main objective of this project is to build a serverless data pipeline using AWS CDK to analyze the data from three different sources. The historical stock data is stored in the Amazon aurora database, the historical FOREX data(Foreign Exchange Market) is stored in an AWS S3 bucket in JSON format, and the intraday stock data comes from the Alpha Vantage API. here we used AWS serverless technologies like Amazon Lambda and Amazon Glue to process and transform the data from the three data sources. We also used Amazon Athena and Quicksight to analyze and visualize the transformed data. 


## Data 

https://www.alphavantage.co/

# Architecture 

!<img width="335" alt="image" src="https://github.com/Rahulreddy1020/Serverless-Data-Pipeline-using-AWS-Lambda-and-Provisioning-infra-with-AWS-CDK/assets/83365184/fce0b5e4-81fe-40c3-b5a4-e496a381415e">



# Welcome to your CDK Python project!

This is a blank project for CDK development with Python.

The `cdk.json` file tells the CDK Toolkit how to execute your app.

This project is set up like a standard Python project.  The initialization
process also creates a virtualenv within this project, stored under the `.venv`
directory.  To create the virtualenv it assumes that there is a `python3`
(or `python` for Windows) executable in your path with access to the `venv`
package. If for any reason the automatic creation of the virtualenv fails,
you can create the virtualenv manually.

To manually create a virtualenv on MacOS and Linux:

```
$ python3 -m venv .venv
```

After the init process completes and the virtualenv is created, you can use the following
step to activate your virtualenv.

```
$ source .venv/bin/activate
```

If you are a Windows platform, you would activate the virtualenv like this:

```
% .venv\Scripts\activate.bat
```

Once the virtualenv is activated, you can install the required dependencies.

```
$ pip install -r requirements.txt
```

At this point you can now synthesize the CloudFormation template for this code.

```
$ cdk synth
```

To add additional dependencies, for example other CDK libraries, just add
them to your `setup.py` file and rerun the `pip install -r requirements.txt`
command.

## Useful commands

 * `cdk ls`          list all stacks in the app
 * `cdk synth`       emits the synthesized CloudFormation template
 * `cdk deploy`      deploy this stack to your default AWS account/region
 * `cdk diff`        compare deployed stack with current state
 * `cdk docs`        open CDK documentation

Enjoy!
