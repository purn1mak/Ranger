# Ranger Schedulable Policy

### Use Cases
* Access to a resource may be dependent on the time of access
* Pre-determined maintenance schedules require that resources may not be accessed during maintenance window
* Globally distributed data-centers need time-zone-aware policies

### Adds time-dimension to security
* Policy allows optional start and end times, and timezone specification
* Supports enforcement in local (where service is executed) or a global timezone
* Schedulable policies is time-zone aware which means that if the user is in different time zone, the time specified in would be applicable to his local time.
* Also there is provision to define the time zone also in the time attribute. In that case the user will get access according to the time zone and not by his local time
* This means the security admin can define the policies once and not worry about disabling it manually.
* Also there is provision to define the time zone also in the time attribute. Stock documents after quarterly release occurs at EST and after that certain documents are accessible 


### Support for schedulable classification
Now Apache Ranger is the defacto framework for Comprehensive Security for Hadoop ecosystem components, with these new features, Apache Ranger has more sophisticated ways to address security related use case   

