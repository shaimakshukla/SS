class Solution(object):
    def isPalindrome(self, x):
        n = str(x)
        return n == n[::-1]
        
