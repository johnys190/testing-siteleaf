---
title: My Website
date: 2019-04-09 17:38:00 +03:00
permalink: "/"
---

A Test content
{code}
2019-04-09 20:44:13,470 ERROR [com.gfggroup.simfonie.external.smsc.manager.impl.SMSConnectionManager] (FlowControlTimer-smsmgr) Error:
com.gfggroup.mobile.core.errors.BusinessException: errorCode: ErrorCode.EXTERNAL_SYSTEM_SMS_NO_TELCO_FOUND, errorCodeParams: +306976570363

	at com.gfggroup.simfonie.external.smsc.manager.impl.SMSConnectionManager.handleNoConnectionError(SMSConnectionManager.java:225)
	at com.gfggroup.simfonie.external.smsc.manager.timer.ExternalSystemMessageTimer.run(ExternalSystemMessageTimer.java:53)
	at java.util.TimerThread.mainLoop(Timer.java:512)
	at java.util.TimerThread.run(Timer.java:462)
{code}