# fast.ai notes

Notes for the [fast.ai](http://fast.ai) course.

# awscli

Course link: [course.fast.ai/lessons/aws.html](http://course.fast.ai/lessons/aws.html)

Notes:
* Using awscli version installed at `~/aws-cli-venv`. To activate: 
    ```
    . ~/aws-cli-venv/bin/activate
    ```
* The virtualenv is optional, but recommended when using a non-disposable
  environment such as a physical laptop.
* To recreate:
    ```
    virtualenv ~/aws-cli-venv
    pip install awscli
    ```
* Profile name is "whatever". `export AWS_PROFILE=whatever` to use.
* Instance not yet created, awaiting account verification & limit increase.
  Details [here](https://us-west-2.console.aws.amazon.com/ec2/v2/home?region=us-west-2#Limits:).

