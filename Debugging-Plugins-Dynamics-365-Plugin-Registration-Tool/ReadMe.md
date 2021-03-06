# Debugging Plugins in Dynamics 365 with Plugin Registration Tool

To debug plugin code in Dynamics 365, We use profiling in Plugin Registration Tool. Here for sample plugin I'm using code from one of the [previous article](https://www.c-sharpcorner.com/article/assigning-case-to-appropriate-team-user-using-plugin-in-dynamics-365-crm/) you can use this or try with your own plugins. If you don't already have Plugin Registration Tool grab it from NuGet(https://www.nuget.org/packages/Microsoft.CrmSdk.XrmTooling.PluginRegistrationTool/).

## Pre-Condition

If you already have some plugin in your environment to debug, you can skip this step. If not download and build the plugin code from [https://github.com/AshV/AssignPluginDynamics365](https://github.com/AshV/AssignPluginDynamics365).

![code-repo](assets/code-repo.png)

Open Plugin Registration Tool, connect to your organization & click on "Register New Assembly"

![register-assembly](assets/register-assembly.png)

Browse for your assembly & click "Register Selected Plugins" to register it.

![registering](assets/registering.png)

## Step 2: Registering Step

![register-step](assets/register-step.png)

![assign-message](assets/assign-message.png)

## Step 3: Installing Profiler

![Install-Profiler](assets/Install-Profiler.png)

![Installing-Profiler](assets/Installing-Profiler.png)

![Installed-Profiler](assets/Installed-Profiler.png)

## Step 4: Start Profiling

![Start-Profiling](assets/Start-Profiling.png)

![Profiling-with-Exception](assets/Profiling-with-Exception.png)