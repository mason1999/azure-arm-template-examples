# ARM

## Overview

This is a repo which is an example of an ARM templates.

## Examples

### Patch Configuration

1. Update `p_subscription_id` with your Azure subscription id.
1. Run the following commands:

   ```
   az deployment mg create \
       --name demoMGDeployment \
       --location australiaeast \
       --management-group-id myMGID \
       --template-file ./my-template-file
   ```
