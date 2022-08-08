#Given an integer array nums, 
return true if any value appears at least twice in the array, 
and return false if every element is distinct.

 


class Solution(object):
    def containsDuplicate(self, nums):
        """
        :type nums: List[int]
        :rtype: bool
        
        """
        dup = 0
        nums.sort()
        
        for i in range(1, len(nums)):
            if nums[i] == nums[i - 1]:
                dup += 1
        return dup != 0
