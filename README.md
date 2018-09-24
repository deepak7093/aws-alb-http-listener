# aws-alb-http-listner
This module is useful to create indivisual http listeners on application load balancer.

## Module Usage

module "listner1" {
  source = "custom_alb_listener_rule_http"
  alb_arn = ""
  port = "80"
  target_group_arn = ""
}


