# playbooks
Ansible playbooks

- aws.cfg | AWS credentials

- az_mean_config.yml | Configures and MEAN stack built by az_mean_deploy.yml as part of a Tower workflow

- az_mean_deploy.yml | Deploys a MEAN stack in azure, to be followed by az_mean_config.yml as part of a Tower workflow

- create_az_db_teama.yml | Create an audit enabled SQL server database in azure

- create_rds_audit.yml | Create an audit enabled SQL server database in aws rds

- create_rds_schedule_teama | Create a Tower schedule to delete aws rds databases at a certain date/time

- create_rds_teama | Create a simple aws rds database

- f5_day2_config.yml | Maintains a configuration on an existing bigip device

- permission_policy.json | used by the role_policy.yml playbook

- role_policy.yml | Maintains a role/trust/policy in aws iam

- stop_rds_teama.yml | Deletes all aws rds databases tagged to TeamA

- tower_cli.cfg | Credentials for Tower so the tower cli can be used

- trust_policy.json | used by the role_policy.yml playbook
