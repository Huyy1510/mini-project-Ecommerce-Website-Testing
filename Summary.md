 **Test Summary Report – OpenCart Demo**

1. Test Execution Overview

Total Test Cases: 12

Executed: 12

Passed: 9

Failed: 3

2. Bug Statistics

Total Bugs Found: 3

By Severity:

Critical: 1 (Checkout không validate địa chỉ)

High: 1 (Registration không báo lỗi khi bỏ trống Password)

Medium: 1 (Cart không update tổng giá)

3. Major Findings

Hệ thống cho phép Checkout với dữ liệu thiếu → bug critical.

Validation form chưa đầy đủ, đặc biệt ở Registration.

Cart có lỗi tính toán giá trị tổng khi update số lượng.

4. Conclusion

Website OpenCart Demo còn tồn tại bug quan trọng, chưa đáp ứng yêu cầu chất lượng ở chức năng Checkout và Registration.

Khuyến nghị: Fix toàn bộ bug critical/high trước khi đưa vào production.
