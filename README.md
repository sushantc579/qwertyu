# qwertyu
{
  "name": "Elastic-Beanstalk-Sample-App",
  "version": "0.0.1",
  "dependencies": {
    "aws-sdk": {
      "version": "2.1.39",
      "from": "aws-sdk@latest",
      "resolved": "https://registry.npmjs.org/aws-sdk/-/aws-sdk-2.1.39.tgz",
      "dependencies": {
        "sax": {
          "version": "0.5.3",
          "from": "sax@0.5.3",
          "resolved": "https://registry.npmjs.org/sax/-/sax-0.5.3.tgz"
        },
        "xml2js": {
          "version": "0.2.8",
          "from": "xml2js@0.2.8",
          "resolved": "https://registry.npmjs.org/xml2js/-/xml2js-0.2.8.tgz"
        },
        "xmlbuilder": {
          "version": "0.4.2",
          "from": "xmlbuilder@0.4.2",
          "resolved": "https://registry.npmjs.org/xmlbuilder/-/xmlbuilder-0.4.2.tgz"
        }
      }
    },
    "body-parser": {
      "version": "1.13.2",
      "from": "body-parser@latest",
      "resolved": "https://registry.npmjs.org/body-parser/-/body-parser-1.13.2.tgz",
      "dependencies": {
        "bytes": {
          "version": "2.1.0",
          "from": "bytes@2.1.0",
          "resolved": "https://registry.npmjs.org/bytes/-/bytes-2.1.0.tgz"
        },
        "content-type": {
          "version": "1.0.1",
          "from": "content-type@~1.0.1",
          "resolved": "https://registry.npmjs.org/content-type/-/content-type-1.0.1.tgz"
        },
        "debug": {
          "version": "2.2.0",
          "from": "debug@~2.2.0",
          "resolved": "https://registry.npmjs.org/debug/-/debug-2.2.0.tgz",
          "dependencies": {
            "ms": {
              "version": "0.7.1",
              "from": "ms@0.7.1",
              "resolved": "https://registry.npmjs.org/ms/-/ms-0.7.1.tgz"
            }
          }
        },
        "depd": {
          "version": "1.0.1",
          "from": "depd@~1.0.1",
          "resolved": "https://registry.npmjs.org/depd/-/depd-1.0.1.tgz"
        },
        "http-errors": {
          "version": "1.3.1",
          "from": "http-errors@~1.3.1",
          "resolved": "https://registry.npmjs.org/http-errors/-/http-errors-1.3.1.tgz",
          "dependencies": {
            "inherits": {
              "version": "2.0.1",
              "from": "inherits@~2.0.1",
              "resolved": "https://registry.npmjs.org/inherits/-/inherits-2.0.1.tgz"
            },
            "statuses": {
              "version": "1.2.1",
              "from": "statuses@1",
              "resolved": "https://registry.npmjs.org/statuses/-/statuses-1.2.1.tgz"
            }
          }
        },
        "iconv-lite": {
          "version": "0.4.11",
          "from": "iconv-lite@0.4.11",
          "resolved": "https://registry.npmjs.org/iconv-lite/-/iconv-lite-0.4.11.tgz"
        },
        "on-finished": {
          "version": "2.3.0",
          "from": "on-finished@~2.3.0",
          "resolved": "https://registry.npmjs.org/on-finished/-/on-finished-2.3.0.tgz",
          "dependencies": {
            "ee-first": {
              "version": "1.1.1",
              "from": "ee-first@1.1.1",
              "resolved": "https://registry.npmjs.org/ee-first/-/ee-first-1.1.1.tgz"
            }
          }
        },
        "qs": {
          "version": "4.0.0",
          "from": "qs@4.0.0",
          "resolved": "https://registry.npmjs.org/qs/-/qs-4.0.0.tgz"
        },
        "raw-body": {
          "version": "2.1.2",
          "from": "raw-body@~2.1.2",
          "resolved": "https://registry.npmjs.org/raw-body/-/raw-body-2.1.2.tgz",
          "dependencies": {
            "unpipe": {
              "version": "1.0.0",
              "from": "unpipe@1.0.0",
              "resolved": "https://registry.npmjs.org/unpipe/-/unpipe-1.0.0.tgz"
            }
          }
        },
        "type-is": {
          "version": "1.6.5",
          "from": "type-is@~1.6.4",
          "resolved": "https://registry.npmjs.org/type-is/-/type-is-1.6.5.tgz",
          "dependencies": {
            "media-typer": {
              "version": "0.3.0",
              "from": "media-typer@0.3.0",
              "resolved": "https://registry.npmjs.org/media-typer/-/media-typer-0.3.0.tgz"
            },
            "mime-types": {
              "version": "2.1.3",
              "from": "mime-types@~2.1.3",
              "resolved": "https://registry.npmjs.org/mime-types/-/mime-types-2.1.3.tgz",
              "dependencies": {
                "mime-db": {
                  "version": "1.15.0",
                  "from": "mime-db@~1.15.0",
                  "resolved": "https://registry.npmjs.org/mime-db/-/mime-db-1.15.0.tgz"
                }
              }
            }
          }
        }
      }
    },
    "ejs": {
      "version": "2.3.3",
      "from": "ejs@latest",
      "resolved": "https://registry.npmjs.org/ejs/-/ejs-2.3.3.tgz"
    },
    "express": {
      "version": "4.13.1",
      "from": "express@latest",
      "resolved": "https://registry.npmjs.org/express/-/express-4.13.1.tgz",
      "dependencies": {
        "accepts": {
          "version": "1.2.11",
          "from": "accepts@~1.2.10",
          "resolved": "https://registry.npmjs.org/accepts/-/accepts-1.2.11.tgz",
          "dependencies": {
            "mime-types": {
              "version": "2.1.3",
              "from": "mime-types@~2.1.3",
              "resolved": "https://registry.npmjs.org/mime-types/-/mime-types-2.1.3.tgz",
              "dependencies": {
                "mime-db": {
                  "version": "1.15.0",
                  "from": "mime-db@~1.15.0",
                  "resolved": "https://registry.npmjs.org/mime-db/-/mime-db-1.15.0.tgz"
                }
              }
            },
            "negotiator": {
              "version": "0.5.3",
              "from": "negotiator@0.5.3",
              "resolved": "https://registry.npmjs.org/negotiator/-/negotiator-0.5.3.tgz"
            }
          }
        },
        "array-flatten": {
          "version": "1.1.0",
          "from": "array-flatten@1.1.0",
          "resolved": "https://registry.npmjs.org/array-flatten/-/array-flatten-1.1.0.tgz"
        },
        "content-disposition": {
          "version": "0.5.0",
          "from": "content-disposition@0.5.0",
          "resolved": "https://registry.npmjs.org/content-disposition/-/content-disposition-0.5.0.tgz"
        },
        "content-type": {
          "version": "1.0.1",
          "from": "content-type@~1.0.1",
          "resolved": "https://registry.npmjs.org/content-type/-/content-type-1.0.1.tgz"
        },
        "cookie": {
          "version": "0.1.3",
          "from": "cookie@0.1.3",
          "resolved": "https://registry.npmjs.org/cookie/-/cookie-0.1.3.tgz"
        },
        "cookie-signature": {
          "version": "1.0.6",
          "from": "cookie-signature@1.0.6",
          "resolved": "https://registry.npmjs.org/cookie-signature/-/cookie-signature-1.0.6.tgz"
        },
        "debug": {
          "version": "2.2.0",
          "from": "debug@~2.2.0",
          "resolved": "https://registry.npmjs.org/debug/-/debug-2.2.0.tgz",
          "dependencies": {
            "ms": {
              "version": "0.7.1",
              "from": "ms@0.7.1",
              "resolved": "https://registry.npmjs.org/ms/-/ms-0.7.1.tgz"
            }
          }
        },
        "depd": {
          "version": "1.0.1",
          "from": "depd@~1.0.1",
          "resolved": "https://registry.npmjs.org/depd/-/depd-1.0.1.tgz"
        },
        "escape-html": {
          "version": "1.0.2",
          "from": "escape-html@1.0.2",
          "resolved": "https://registry.npmjs.org/escape-html/-/escape-html-1.0.2.tgz"
        },
        "etag": {
          "version": "1.7.0",
          "from": "etag@~1.7.0",
          "resolved": "https://registry.npmjs.org/etag/-/etag-1.7.0.tgz"
        },
        "finalhandler": {
          "version": "0.4.0",
          "from": "finalhandler@0.4.0",
          "resolved": "https://registry.npmjs.org/finalhandler/-/finalhandler-0.4.0.tgz",
          "dependencies": {
            "unpipe": {
              "version": "1.0.0",
              "from": "unpipe@~1.0.0",
              "resolved": "https://registry.npmjs.org/unpipe/-/unpipe-1.0.0.tgz"
            }
          }
        },
        "fresh": {
          "version": "0.3.0",
          "from": "fresh@0.3.0",
          "resolved": "https://registry.npmjs.org/fresh/-/fresh-0.3.0.tgz"
        },
        "merge-descriptors": {
          "version": "1.0.0",
          "from": "merge-descriptors@1.0.0",
          "resolved": "https://registry.npmjs.org/merge-descriptors/-/merge-descriptors-1.0.0.tgz"
        },
        "methods": {
          "version": "1.1.1",
          "from": "methods@~1.1.1",
          "resolved": "https://registry.npmjs.org/methods/-/methods-1.1.1.tgz"
        },
        "on-finished": {
          "version": "2.3.0",
          "from": "on-finished@~2.3.0",
          "resolved": "https://registry.npmjs.org/on-finished/-/on-finished-2.3.0.tgz",
          "dependencies": {
            "ee-first": {
              "version": "1.1.1",
              "from": "ee-first@1.1.1",
              "resolved": "https://registry.npmjs.org/ee-first/-/ee-first-1.1.1.tgz"
            }
          }
        },
        "parseurl": {
          "version": "1.3.0",
          "from": "parseurl@~1.3.0",
          "resolved": "https://registry.npmjs.org/parseurl/-/parseurl-1.3.0.tgz"
        },
        "path-to-regexp": {
          "version": "0.1.6",
          "from": "path-to-regexp@0.1.6",
          "resolved": "https://registry.npmjs.org/path-to-regexp/-/path-to-regexp-0.1.6.tgz"
        },
        "proxy-addr": {
          "version": "1.0.8",
          "from": "proxy-addr@~1.0.8",
          "resolved": "https://registry.npmjs.org/proxy-addr/-/proxy-addr-1.0.8.tgz",
          "dependencies": {
            "forwarded": {
              "version": "0.1.0",
              "from": "forwarded@~0.1.0",
              "resolved": "https://registry.npmjs.org/forwarded/-/forwarded-0.1.0.tgz"
            },
            "ipaddr.js": {
              "version": "1.0.1",
              "from": "ipaddr.js@1.0.1",
              "resolved": "https://registry.npmjs.org/ipaddr.js/-/ipaddr.js-1.0.1.tgz"
            }
          }
        },
        "qs": {
          "version": "4.0.0",
          "from": "qs@4.0.0",
          "resolved": "https://registry.npmjs.org/qs/-/qs-4.0.0.tgz"
        },
        "range-parser": {
          "version": "1.0.2",
          "from": "range-parser@~1.0.2",
          "resolved": "https://registry.npmjs.org/range-parser/-/range-parser-1.0.2.tgz"
        },
        "send": {
          "version": "0.13.0",
          "from": "send@0.13.0",
          "resolved": "https://registry.npmjs.org/send/-/send-0.13.0.tgz",
          "dependencies": {
            "destroy": {
              "version": "1.0.3",
              "from": "destroy@1.0.3",
              "resolved": "https://registry.npmjs.org/destroy/-/destroy-1.0.3.tgz"
            },
            "http-errors": {
              "version": "1.3.1",
              "from": "http-errors@~1.3.1",
              "resolved": "https://registry.npmjs.org/http-errors/-/http-errors-1.3.1.tgz",
              "dependencies": {
                "inherits": {
                  "version": "2.0.1",
                  "from": "inherits@~2.0.1",
                  "resolved": "https://registry.npmjs.org/inherits/-/inherits-2.0.1.tgz"
                }
              }
            },
            "mime": {
              "version": "1.3.4",
              "from": "mime@1.3.4",
              "resolved": "https://registry.npmjs.org/mime/-/mime-1.3.4.tgz"
            },
            "ms": {
              "version": "0.7.1",
              "from": "ms@0.7.1",
              "resolved": "https://registry.npmjs.org/ms/-/ms-0.7.1.tgz"
            },
            "statuses": {
              "version": "1.2.1",
              "from": "statuses@~1.2.1",
              "resolved": "https://registry.npmjs.org/statuses/-/statuses-1.2.1.tgz"
            }
          }
        },
        "serve-static": {
          "version": "1.10.0",
          "from": "serve-static@~1.10.0",
          "resolved": "https://registry.npmjs.org/serve-static/-/serve-static-1.10.0.tgz"
        },
        "type-is": {
          "version": "1.6.5",
          "from": "type-is@~1.6.4",
          "resolved": "https://registry.npmjs.org/type-is/-/type-is-1.6.5.tgz",
          "dependencies": {
            "media-typer": {
              "version": "0.3.0",
              "from": "media-typer@0.3.0",
              "resolved": "https://registry.npmjs.org/media-typer/-/media-typer-0.3.0.tgz"
            },
            "mime-types": {
              "version": "2.1.3",
              "from": "mime-types@~2.1.3",
              "resolved": "https://registry.npmjs.org/mime-types/-/mime-types-2.1.3.tgz",
              "dependencies": {
                "mime-db": {
                  "version": "1.15.0",
                  "from": "mime-db@~1.15.0",
                  "resolved": "https://registry.npmjs.org/mime-db/-/mime-db-1.15.0.tgz"
                }
              }
            }
          }
        },
        "vary": {
          "version": "1.0.1",
          "from": "vary@~1.0.0",
          "resolved": "https://registry.npmjs.org/vary/-/vary-1.0.1.tgz"
        },
        "utils-merge": {
          "version": "1.0.0",
          "from": "utils-merge@1.0.0",
          "resolved": "https://registry.npmjs.org/utils-merge/-/utils-merge-1.0.0.tgz"
        }
      }
    }
  }
}

{
  "name": "Elastic-Beanstalk-Sample-App",
  "version": "0.0.1",
  "private": true,
  "dependencies": {
    "ejs": "latest",
    "aws-sdk": "latest",
    "express": "latest",
    "body-parser": "latest"
  },
  "scripts": {
    "start": "node app.js"
  }
}

# AWS Elastic Beanstalk Express Sample App
This sample application uses the [Express](https://expressjs.com/) framework and [Bootstrap](http://getbootstrap.com/) to build a simple, scalable customer signup form that is deployed to [AWS Elastic Beanstalk](http://aws.amazon.com/elasticbeanstalk/). The application stores data in [Amazon DynamoDB](http://aws.amazon.com/dynamodb/) and publishes notifications to the [Amazon Simple Notification Service (SNS)](http://aws.amazon.com/sns/) when a customer fills out the form.

## Features
### Themes
The code includes several Bootstrap themes from [bootswatch.com](http://bootswatch.com/). You can dynamically change the active theme by setting the THEME environment variable in the [Elastic Beanstalk Management Console](https://console.aws.amazon.com/elasticbeanstalk):

![](misc/theme-flow.png)

Installed themes include:

* [amelia](http://bootswatch.com/amelia)
* [default](http://bootswatch.com/default)
* [flatly](http://bootswatch.com/flatly)
* [slate](http://bootswatch.com/slate)
* [united](http://bootswatch.com/united)

You can get started using the following steps:
  1. [Install the AWS Elastic Beanstalk Command Line Interface (CLI)](http://docs.aws.amazon.com/elasticbeanstalk/latest/dg/eb-cli3-install.html).
  2. Create an IAM Instance Profile named **aws-elasticbeanstalk-sample-role** with the policy in [iam_policy.json](iam_policy.json). For more information on how to create an IAM Instance Profile, see [Create an IAM Instance Profile for Your Amazon EC2 Instances](https://docs.aws.amazon.com/codedeploy/latest/userguide/how-to-create-iam-instance-profile.html).
  3. Run `eb init -r <region> -p "Node.js"` to initialize the folder for use with the CLI. Replace `<region>` with a region identifier such as `us-west-2` (see [Regions and Endpoints](https://docs.amazonaws.cn/en_us/general/latest/gr/rande.html#elasticbeanstalk_region) for a full list of region identifiers). For interactive mode, run `eb init` then,
    1. Pick a region of your choice.
    2. Select the **[ Create New Application ]** option.
    3. Enter the application name of your choice.
    4. Answer **yes** to *It appears you are using Node.js. Is this correct?*.
    7. Choose whether you want SSH access to the Amazon EC2 instances.  
      *Note: If you choose to enable SSH and do not have an existing SSH key stored on AWS, the EB CLI requires ssh-keygen to be available on the path to generate SSH keys.*  
  4. Run `eb create --instance_profile aws-elasticbeanstalk-sample-role` to begin the creation of your environment.
    1. Enter the environment name of your choice.
    2. Enter the CNAME prefix you want to use for this environment.
  5. Once the environment creation process completes, run `eb open` to open the application in a browser.
  6. Run `eb terminate --all` to clean up.

.DS_Store

# Elastic Beanstalk CLI Files
.elasticbeanstalk/*

// Include the cluster module
var cluster = require('cluster');

// Code to run if we're in the master process
if (cluster.isMaster) {

    // Count the machine's CPUs
    var cpuCount = require('os').cpus().length;

    // Create a worker for each CPU
    for (var i = 0; i < cpuCount; i += 1) {
        cluster.fork();
    }

    // Listen for terminating workers
    cluster.on('exit', function (worker) {

        // Replace the terminated workers
        console.log('Worker ' + worker.id + ' died :(');
        cluster.fork();

    });

// Code to run if we're in a worker process
} else {
    var AWS = require('aws-sdk');
    var express = require('express');
    var bodyParser = require('body-parser');

    AWS.config.region = process.env.REGION

    var sns = new AWS.SNS();
    var ddb = new AWS.DynamoDB();

    var ddbTable =  process.env.STARTUP_SIGNUP_TABLE;
    var snsTopic =  process.env.NEW_SIGNUP_TOPIC;
    var app = express();

    app.set('view engine', 'ejs');
    app.set('views', __dirname + '/views');
    app.use(bodyParser.urlencoded({extended:false}));

    app.get('/', function(req, res) {
        res.render('index', {
            static_path: 'static',
            theme: process.env.THEME || 'flatly',
            flask_debug: process.env.FLASK_DEBUG || 'false'
        });
    });

    app.post('/signup', function(req, res) {
        var item = {
            'email': {'S': req.body.email},
            'name': {'S': req.body.name},
            'preview': {'S': req.body.previewAccess},
            'theme': {'S': req.body.theme}
        };

        ddb.putItem({
            'TableName': ddbTable,
            'Item': item,
            'Expected': { email: { Exists: false } }        
        }, function(err, data) {
            if (err) {
                var returnStatus = 500;

                if (err.code === 'ConditionalCheckFailedException') {
                    returnStatus = 409;
                }

                res.status(returnStatus).end();
                console.log('DDB Error: ' + err);
            } else {
                sns.publish({
                    'Message': 'Name: ' + req.body.name + "\r\nEmail: " + req.body.email 
                                        + "\r\nPreviewAccess: " + req.body.previewAccess 
                                        + "\r\nTheme: " + req.body.theme,
                    'Subject': 'New user sign up!!!',
                    'TopicArn': snsTopic
                }, function(err, data) {
                    if (err) {
                        res.status(500).end();
                        console.log('SNS Error: ' + err);
                    } else {
                        res.status(201).end();
                    }
                });            
            }
        });
    });

    var port = process.env.PORT || 3000;

    var server = app.listen(port, function () {
        console.log('Server running at http://127.0.0.1:' + port + '/');
    });
}
{
  "Version": "2012-10-17",
  "Statement": [
    {
      "Effect": "Allow",
      "Action":   [ "dynamodb:PutItem" ],
      "Resource": [ "*" ]
    },
    {
      "Effect": "Allow",
      "Action":   [ "sns:Publish" ],
      "Resource": [ "*" ]
    }
  ]
}
                                 Apache License
                           Version 2.0, January 2004
                        http://www.apache.org/licenses/

   TERMS AND CONDITIONS FOR USE, REPRODUCTION, AND DISTRIBUTION

   1. Definitions.

      "License" shall mean the terms and conditions for use, reproduction,
      and distribution as defined by Sections 1 through 9 of this document.

      "Licensor" shall mean the copyright owner or entity authorized by
      the copyright owner that is granting the License.

      "Legal Entity" shall mean the union of the acting entity and all
      other entities that control, are controlled by, or are under common
      control with that entity. For the purposes of this definition,
      "control" means (i) the power, direct or indirect, to cause the
      direction or management of such entity, whether by contract or
      otherwise, or (ii) ownership of fifty percent (50%) or more of the
      outstanding shares, or (iii) beneficial ownership of such entity.

      "You" (or "Your") shall mean an individual or Legal Entity
      exercising permissions granted by this License.

      "Source" form shall mean the preferred form for making modifications,
      including but not limited to software source code, documentation
      source, and configuration files.

      "Object" form shall mean any form resulting from mechanical
      transformation or translation of a Source form, including but
      not limited to compiled object code, generated documentation,
      and conversions to other media types.

      "Work" shall mean the work of authorship, whether in Source or
      Object form, made available under the License, as indicated by a
      copyright notice that is included in or attached to the work
      (an example is provided in the Appendix below).

      "Derivative Works" shall mean any work, whether in Source or Object
      form, that is based on (or derived from) the Work and for which the
      editorial revisions, annotations, elaborations, or other modifications
      represent, as a whole, an original work of authorship. For the purposes
      of this License, Derivative Works shall not include works that remain
      separable from, or merely link (or bind by name) to the interfaces of,
      the Work and Derivative Works thereof.

      "Contribution" shall mean any work of authorship, including
      the original version of the Work and any modifications or additions
      to that Work or Derivative Works thereof, that is intentionally
      submitted to Licensor for inclusion in the Work by the copyright owner
      or by an individual or Legal Entity authorized to submit on behalf of
      the copyright owner. For the purposes of this definition, "submitted"
      means any form of electronic, verbal, or written communication sent
      to the Licensor or its representatives, including but not limited to
      communication on electronic mailing lists, source code control systems,
      and issue tracking systems that are managed by, or on behalf of, the
      Licensor for the purpose of discussing and improving the Work, but
      excluding communication that is conspicuously marked or otherwise
      designated in writing by the copyright owner as "Not a Contribution."

      "Contributor" shall mean Licensor and any individual or Legal Entity
      on behalf of whom a Contribution has been received by Licensor and
      subsequently incorporated within the Work.

   2. Grant of Copyright License. Subject to the terms and conditions of
      this License, each Contributor hereby grants to You a perpetual,
      worldwide, non-exclusive, no-charge, royalty-free, irrevocable
      copyright license to reproduce, prepare Derivative Works of,
      publicly display, publicly perform, sublicense, and distribute the
      Work and such Derivative Works in Source or Object form.

   3. Grant of Patent License. Subject to the terms and conditions of
      this License, each Contributor hereby grants to You a perpetual,
      worldwide, non-exclusive, no-charge, royalty-free, irrevocable
      (except as stated in this section) patent license to make, have made,
      use, offer to sell, sell, import, and otherwise transfer the Work,
      where such license applies only to those patent claims licensable
      by such Contributor that are necessarily infringed by their
      Contribution(s) alone or by combination of their Contribution(s)
      with the Work to which such Contribution(s) was submitted. If You
      institute patent litigation against any entity (including a
      cross-claim or counterclaim in a lawsuit) alleging that the Work
      or a Contribution incorporated within the Work constitutes direct
      or contributory patent infringement, then any patent licenses
      granted to You under this License for that Work shall terminate
      as of the date such litigation is filed.

   4. Redistribution. You may reproduce and distribute copies of the
      Work or Derivative Works thereof in any medium, with or without
      modifications, and in Source or Object form, provided that You
      meet the following conditions:

      (a) You must give any other recipients of the Work or
          Derivative Works a copy of this License; and

      (b) You must cause any modified files to carry prominent notices
          stating that You changed the files; and

      (c) You must retain, in the Source form of any Derivative Works
          that You distribute, all copyright, patent, trademark, and
          attribution notices from the Source form of the Work,
          excluding those notices that do not pertain to any part of
          the Derivative Works; and

      (d) If the Work includes a "NOTICE" text file as part of its
          distribution, then any Derivative Works that You distribute must
          include a readable copy of the attribution notices contained
          within such NOTICE file, excluding those notices that do not
          pertain to any part of the Derivative Works, in at least one
          of the following places: within a NOTICE text file distributed
          as part of the Derivative Works; within the Source form or
          documentation, if provided along with the Derivative Works; or,
          within a display generated by the Derivative Works, if and
          wherever such third-party notices normally appear. The contents
          of the NOTICE file are for informational purposes only and
          do not modify the License. You may add Your own attribution
          notices within Derivative Works that You distribute, alongside
          or as an addendum to the NOTICE text from the Work, provided
          that such additional attribution notices cannot be construed
          as modifying the License.

      You may add Your own copyright statement to Your modifications and
      may provide additional or different license terms and conditions
      for use, reproduction, or distribution of Your modifications, or
      for any such Derivative Works as a whole, provided Your use,
      reproduction, and distribution of the Work otherwise complies with
      the conditions stated in this License.

   5. Submission of Contributions. Unless You explicitly state otherwise,
      any Contribution intentionally submitted for inclusion in the Work
      by You to the Licensor shall be under the terms and conditions of
      this License, without any additional terms or conditions.
      Notwithstanding the above, nothing herein shall supersede or modify
      the terms of any separate license agreement you may have executed
      with Licensor regarding such Contributions.

   6. Trademarks. This License does not grant permission to use the trade
      names, trademarks, service marks, or product names of the Licensor,
      except as required for reasonable and customary use in describing the
      origin of the Work and reproducing the content of the NOTICE file.

   7. Disclaimer of Warranty. Unless required by applicable law or
      agreed to in writing, Licensor provides the Work (and each
      Contributor provides its Contributions) on an "AS IS" BASIS,
      WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or
      implied, including, without limitation, any warranties or conditions
      of TITLE, NON-INFRINGEMENT, MERCHANTABILITY, or FITNESS FOR A
      PARTICULAR PURPOSE. You are solely responsible for determining the
      appropriateness of using or redistributing the Work and assume any
      risks associated with Your exercise of permissions under this License.

   8. Limitation of Liability. In no event and under no legal theory,
      whether in tort (including negligence), contract, or otherwise,
      unless required by applicable law (such as deliberate and grossly
      negligent acts) or agreed to in writing, shall any Contributor be
      liable to You for damages, including any direct, indirect, special,
      incidental, or consequential damages of any character arising as a
      result of this License or out of the use or inability to use the
      Work (including but not limited to damages for loss of goodwill,
      work stoppage, computer failure or malfunction, or any and all
      other commercial damages or losses), even if such Contributor
      has been advised of the possibility of such damages.

   9. Accepting Warranty or Additional Liability. While redistributing
      the Work or Derivative Works thereof, You may choose to offer,
      and charge a fee for, acceptance of support, warranty, indemnity,
      or other liability obligations and/or rights consistent with this
      License. However, in accepting such obligations, You may act only
      on Your own behalf and on Your sole responsibility, not on behalf
      of any other Contributor, and only if You agree to indemnify,
      defend, and hold each Contributor harmless for any liability
      incurred by, or claims asserted against, such Contributor by reason
      of your accepting any such warranty or additional liability.

   END OF TERMS AND CONDITIONS

   APPENDIX: How to apply the Apache License to your work.

      To apply the Apache License to your work, attach the following
      boilerplate notice, with the fields enclosed by brackets "{}"
      replaced with your own identifying information. (Don't include
      the brackets!)  The text should be enclosed in the appropriate
      comment syntax for the file format. We also recommend that a
      file or class name and description of purpose be included on the
      same "printed page" as the copyright notice for easier
      identification within third-party archives.

   Copyright {yyyy} {name of copyright owner}

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.

