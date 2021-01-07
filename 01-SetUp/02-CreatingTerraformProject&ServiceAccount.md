************************************************************************************************************
                                        Login to GCloud
************************************************************************************************************https://console.cloud.google.com


# login and follow prompts
> gcloud auth login  
> gcloud projects list
> gcloud projects create test
> gcloud config set project test or  gcloud config set project iron-gizmo-265816

************************************************************************************************************
              Creation of Service Account and Configuration File for our GCP Environment: 
************************************************************************************************************> IAM & Admin > Service Accounts > Create Service Account:
                                 - Service Account Name: terraform > create
                                 - Select a role       : Editor
                                 - Download the json file (terraform.json)

************************************************************************************************************
                                      terraform.json
************************************************************************************************************
 {
  "type": "service_account",
  "project_id": "iron-gizmo-265816",
  "private_key_id": "76b4719a61282a2187d2c61387580628adf78064",
  "private_key": "-----BEGIN PRIVATE KEY-----\nMIIEvQIBADANBgkqhkiG9w0BAQEFAASCBKcwggSjAgEAAoIBAQDWbnf84CAOlgkp\n5GdsNYXsSKwfDEc1y1u+Yti51MgOfc2vJjKxKPqKFLtfFU68DPSbCqLa3faMpe6W\nVcukb8zATp/kdofP0kG9LM0NGxx+tCjuvqwZzvClhzrba6Yt7mjf0WDQVaFibk28\n+WBL+ee6ws3GttamwuOH3MXrnPJfK9loJoOvlOdraD2KGc4g1wOTK9CwQSx6//Mn\nkdxCZui3yXi6xKFFpSxarFVh1bYcjqS/hevyros3fSQwng8kOsZJMpmTsH1fCdXi\nDK/sJeZWFxCSHiQ5LsRmxuB4FYfhYXUMIUM2ldcW+dwz/91TwxKT9t1uuY1DQbqP\nug9AN3iDAgMBAAECggEAS3d7gSL8BUYmmXjKMVow9PSqpw6yLSuR8VJmhhhuBDOg\nZQkjhBgw/NHJE/Cy0hoZKEu4/yBpOhzX+E7fqdKzE+dX/Jb+u1R7UHHpBLjK8YjE\ncynl9ftP1GHghALB7J5giIzu7sOEVdkOQPjfPD4KoT8YHtyQdQZX/6PigEavQnDN\n7vrA6t9foC8zDFalFguve+wQZ5OY2fvWyJnZWjNCrS1YLeWSDRu8MqhLo56x7nrD\nqir+i05wLkEeRQb+pPmxL0CuWFs3okJ03X0h49Aa+KLDdwteKvr0+iS8kZSBFmo3\nNe8Rz4yCpzOnPvgPqrvZQFShANXD4QwkpNuACy5wyQKBgQD7q7wv98F8B8I2/7SI\nzyzXxMr4+cZbKGemBNdhkRNGEnZ9axO7g1X10oMJLgbv+N4zq/0mEGrOBZlqV9bP\nfXeLGI8YtqHaGzptieOTu0xpN5JC0hkf3rp4/vKg7+wrotW9R6oaBVZhP/UJQ4Gs\nqJDBGwMMYp/Yp7sLeUBPolsXfwKBgQDaHr7WIuJdShhjYjMk0c7Y4aSDh05NgTle7K9\n62R+zH2L+gVZ0TKc5a89HtCI/i81KVS3p/GVrWCzw5scK/wvCVRnvgUldlcU28np\nhBRiSwsddY+DYJpO5uOvbeRx5VwQhwIayqqvhHzCGtSr13M0wWZq3Xpd7C6btAsw\nIvuNnm7A/QKBgFAWA0mkZr7IXUZRMqsCenujFRALs9JYVjtfeQaEOwTmZSxeAaZ/\nEcCrH6WxLuX4ZQU+as1NFh+/amWL1ECs5Xiu9QJhQ7n7RimLYo8lYBhvZay73ODm\naKKORrlt/9KW+7tC7d9f6XADAT/UapR+A6pfpSWw0LsKDRyGli+BM8mTAoGBAI48\nuHPJwdXVqxjE/hGTYGEERThWqrC/jprc0ucBEOnj+/NLQXchLLptys1a/IvtTOqK\n4TabHlF7wD2JzWUa72jLeG2qkzTt8uiNkgFbMH9gd1rT9yx20olG308Ko5O/hrbT\n7KSSgAzQFFmPIPiJGfGcRjzTVL2Clj0owuPiKhU9AoGAcwBFRKT9MkKBgwzmR+jJ\nyqoFmm2S0WOwe774mGPqD/w3SvfR+AnMx0qoo9RF/PKXfl+pn1sFo8h1G7JTErjk\nP1zXV/5H4XWsNia9WpyBHAXTyagfE5TA0h3vecYtzpmaVeWhK7vB2ynoPXWJH5iN\ns3bgem3SWTqtzejuheAY8YA=\n-----END PRIVATE KEY-----\n",
  "client_email": "terraform@iron-gizmo-265816.iam.gserviceaccount.com",
  "client_id": "111818295197890770525",
  "auth_uri": "https://accounts.google.com/o/oauth2/auth",
  "token_uri": "https://oauth2.googleapis.com/token",
  "auth_provider_x509_cert_url": "https://www.googleapis.com/oauth2/v1/certs",
  "client_x509_cert_url": "https://www.googleapis.com/robot/v1/metadata/x509/terraform%40iron-gizmo-265816.iam.gserviceaccount.com"
}

