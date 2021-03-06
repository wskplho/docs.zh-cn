---
title: 记录来自应用程序的信息 (Visual Basic)
ms.date: 07/20/2015
helpviewer_keywords:
- Log object
- My.Log object
- applications [Visual Basic], logging information from
- logging
- My.Application.Log object
- examples [Visual Basic], logging application information
ms.assetid: 8bf4f047-22d6-48d6-aec5-93b98ad5b8e8
ms.openlocfilehash: d7cdf5a309da1f32b337bea4d609fe34487a5457
ms.sourcegitcommit: 6b308cf6d627d78ee36dbbae8972a310ac7fd6c8
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 01/23/2019
ms.locfileid: "54746802"
---
# <a name="logging-information-from-the-application-visual-basic"></a>记录来自应用程序的信息 (Visual Basic)
本节包含的主题介绍如何使用 `My.Application.Log` 或 `My.Log` 对象记录来自应用程序的信息，以及如何扩展应用程序的日志记录功能。  
  
 `Log` 对象提供用于将信息写入应用程序的日志侦听器的方法，而 `Log` 对象的高级 `TraceSource` 属性提供详细的配置信息。 `Log` 对象由应用程序的配置文件配置。  
  
 `My.Log` 对象仅适用于 ASP.NET 应用程序。 对于客户端应用程序，请使用 `My.Application.Log`。 有关更多信息，请参见<xref:Microsoft.VisualBasic.Logging.Log>。  
  
## <a name="tasks"></a>任务  
  
|到|查看|  
|--------|---------|  
|将事件信息写入应用程序日志。|[如何：写入日志消息](../../../../visual-basic/developing-apps/programming/log-info/how-to-write-log-messages.md)|  
|将异常信息写入应用程序日志。|[如何：日志异常](../../../../visual-basic/developing-apps/programming/log-info/how-to-log-exceptions.md)|  
|在应用程序启动和关闭时，将跟踪信息写入应用程序日志。|[如何：在应用程序启动或关闭时记录消息](../../../../visual-basic/developing-apps/programming/log-info/how-to-log-messages-when-the-application-starts-or-shuts-down.md)|  
|配置 `My.Application.Log`，将信息写入文本文件。|[如何：将事件信息写入文本文件](../../../../visual-basic/developing-apps/programming/log-info/how-to-write-event-information-to-a-text-file.md)|  
|配置 `My.Application.Log`，将信息写入事件日志。|[如何：将信息写入应用程序事件日志](../../../../visual-basic/developing-apps/programming/log-info/how-to-write-to-an-application-event-log.md)|  
|更改 `My.Application.Log` 写入信息的位置。|[演练：更改 My.Application.Log 在哪里写入信息](../../../../visual-basic/developing-apps/programming/log-info/walkthrough-changing-where-my-application-log-writes-information.md)|  
|确定 `My.Application.Log` 写入信息的位置。|[演练：确定 My.Application.Log 在哪里写入信息](../../../../visual-basic/developing-apps/programming/log-info/walkthrough-determining-where-my-application-log-writes-information.md)|  
|为 `My.Application.Log` 创建自定义日志侦听器。|[演练：创建自定义日志侦听器](../../../../visual-basic/developing-apps/programming/log-info/walkthrough-creating-custom-log-listeners.md)|  
|筛选 `My.Application.Log` 日志的输出。|[演练：筛选 My.Application.Log 输出](../../../../visual-basic/developing-apps/programming/log-info/walkthrough-filtering-my-application-log-output.md)|  
  
## <a name="see-also"></a>请参阅
- <xref:Microsoft.VisualBasic.Logging.Log?displayProperty=nameWithType>
- [使用应用程序日志](../../../../visual-basic/developing-apps/programming/log-info/working-with-application-logs.md)
- [排除故障：日志侦听器](../../../../visual-basic/developing-apps/programming/log-info/troubleshooting-log-listeners.md)
