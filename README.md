# CIS-2.0-Azure-Policy
Azure Policy for CIS 2.0 Foundations Benchmark
Mapping CIS 2.0 Azure benchmarks to Azure Policies

In some cases, out of the box azure policies already exist for these controls. If that is the case, I've just included the default azure policy for reference. If a default azure policy does not exist, then I've created it. See the lists below to diffrentiate which ones are custom vs out of the box.

As always please test and modify any policies as needed that I've created before using them in your prod environment.

Custom Policies:

  Storage Accounts:

    3-3_Enable_Key_Rotation_Reminders.pd.json


Default Policies:

  Storage Accounts:

    3-1_Secure_Transfer_Required.pd

    3-2_Enable_Infrastructure_Encryption.pd

    3-4_Storage_Account_Access_Keys_Periodically_Regenerated.pd
    