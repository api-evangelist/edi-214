---
title: 'RFI #2819: Handling of Negative Zero (-0.00) Amounts (837)'
url: https://x12.org/resources/requests-for-interpretation/rfi-2819-handling-negative-zero-000-amounts-837
date: '2026-05-01'
author: X12 Editor
feed_url: https://x12.org/rss.xml
---
RFI # 2819 Handling of Negative Zero (-0.00) Amounts Description Is it ok/allowable to have -0.00 (negative zero) in the amount fields within the 837 X12 standard? Scenario Section B.1.1.3.1.2 Decimal explicitly states that (+) should not be transmitted, but it is not stated that a (-) cannot be transmitted and more specifically -0.00. RFI Response Based upon the definition for decimal fields in Section B.1.1.3.1.2 Decimal, “For negative values, the leading minus sign (-) is used.” Zero is not negative, so you should not send with a negative sign. RFI Recommendation Do not send a sign with amounts of zero. DOCUMENT ID 005010X299
