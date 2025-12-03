# ARM

## Overview

This is a repo which is an example of an ARM template. It deploys an example resource group, maintenance configuration and configuration assignment (i.e dynamic scope) to help with patching of virtual machines.

## How to use

To use this repository do the following:

1. Update `p_subscription_id` with your Azure subscription id.
1. Run the following commands:

   ```
   az deployment mg create \
       --name demoMGDeployment \
       --location australiaeast \
       --management-group-id myMGID \
       --template-file ./my-template-file
   ```
