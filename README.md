# Reverse String



استخدمت طريقة Two Pointers عشان أعكس الـstring في مكانه.

بدأت بـ left من أول الـarray و right من آخرها، وكل مرة بعمل swap بين الحرفين، وبعدها بحرك left خطوة لقدام و right خطوة لورا.

بفضل أكرر نفس الخطوات لحد ما المؤشرين يقابلوا بعض.

استخدمت char[] واشتغلت عليه مباشرة، من غير ما أستخدم أي function جاهزة للـreverse.

 Complexity

 Time Complexity: O(n)
 Space Complexity: O(1)

 LeetCode

344-Reverse String
