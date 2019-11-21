首云Open API目录
=================

   * [首云公开API文档](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#%E9%A6%96%E4%BA%91%E5%85%AC%E5%BC%80api%E6%96%87%E6%A1%A3)
      * [认证方式](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#认证方式)
         * [1.公共请求参数](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#1公共请求参数)
         * [2.签名机制](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#2签名机制)
            * [步骤一：构造规范化请求字符串](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#步骤一构造规范化请求字符串)
            * [步骤二：构造签名字符串](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#步骤二构造签名字符串)
         * [3.获取签名代码](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#2获取签名代码)
      * [实例相关](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#实例相关)
         * [1.CreateInstance](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#1createinstance)
         * [2.DeleteInstance](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#2deleteinstance)
         * [3. StopInstance](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#3-stopinstance)
         * [4.RebootInstance](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#4rebootinstance)
         * [5.ModifyInstanceChargeType](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#5modifyinstancechargetype)
         * [7.CreateDisk](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#7createdisk)
         * [8.ResizeDisk](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#8resizedisk)
         * [9.DeleteDisk](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#9deletedisk)
         * [11.DescribeInstances](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#11describeinstances)
         * [12.ConnectNetworkInterface](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#12connectnetworkinterface)
         * [13.<strong>DisconnectNetworkInterface</strong>](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#13disconnectnetworkinterface)
         * [14. ModifyIpAddress](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#14-modifyipaddress)
         * [15.DescribeInstanceMonitor](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#15describeinstancemonitor)
      * [安全组相关](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#安全组相关)
         * [1.CreateSecurityGroup](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#1createsecuritygroup)
         * [2.DeleteSecurityGroup](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#2deletesecuritygroup)
         * [3.ForceDeleteSecurityGroup](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#3forcedeletesecuritygroup)
         * [4.DescribeSecurityGroupAttribute](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#4describesecuritygroupattribute)
         * [5.ModifySecurityGroupAttribute](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#5modifysecuritygroupattribute)
         * [6.DescribeSecurityGroups](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#6describesecuritygroups)
         * [7.AddSecurityGroupRule](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#7addsecuritygrouprule)
         * [8.RemoveSecurityGroupRule](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#8removesecuritygrouprule)
         * [9.ModifySecurityGroupRule](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#9modifysecuritygrouprule)
         * [10.JoinSecurityGroup](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#10joinsecuritygroup)
         * [11.LeaveSecurityGroup](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#11leavesecuritygroup)
         * [12.ModifySecurityGroupRulePriority](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#12modifysecuritygrouprulepriority)
      * [模板相关](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#模板相关)
         * [1.CreateTemplate](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#1createtemplate)
         * [2.DeleteTemplate](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#2deletetemplate)
         * [3.SyncTemplate](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#3synctemplate)
         * [4.DescribeTemplateInfo](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#4describetemplateinfo)
      * [虚拟数据中心相关](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#虚拟数据中心相关)
         * [1.DescribeVdc](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#1describevdc)
         * [2.CreateVdc](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#2createvdc)
         * [3.DeleteVdc](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#3deletevdc)
         * [4.CreatePublicNetwork](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#4createpublicnetwork)
         * [5.CreatePrivateNetwork](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#5createprivatenetwork)
         * [6.ModifyPublicNetwork](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#6modifypublicnetwork)
         * [7.AddPublicIp](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#7addpublicip)
         * [8.DeletePublicIp](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#8deletepublicip)
         * [9.DeletePublicNetwork](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#9deletepublicnetwork)
         * [10.DeletePrivateNetwork](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#10deleteprivatenetwork)
         * [11.RenewPublicNetwork](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#11renewpublicnetwork)
         * [12.DescribeBandwidthTraffic](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#12describebandwidthtraffic)
      * [账单相关](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#账单相关)
         * [1.DescribeBill](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#1describebill)
         * [2.DescribeBillInfo](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#2describebillinfo)
      * [其他公共接口](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#其他公共接口)
         * [1.DescribeAvailableResource](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#1describeavailableresource)
         * [2.<strong>DescribeTask</strong>](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#2describetask)
      * [附件一](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#附件一)
            * [节点名称](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#节点名称)
      * [附件二](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#附件二)
            * [主机类型](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#主机类型)
      * [附件三](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#附件三)
            * [带宽类型](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#带宽类型)
      * [附件四](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#附件四)
            * [公共模板](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#公共模板)
      * [示例](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#示例)
         * [1.获取请求url](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#1获取请求url)
         * [4.创建云主机实例](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#4创建云主机实例)
         * [5.修改公网带宽](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#5修改公网带宽)
         * [6.修改云主机实例计费类型](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#6修改云主机实例计费类型)
         * [7.获取任务状态](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#7获取任务状态)
         * [8.定制模板](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#8定制模板)
