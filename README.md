# minimum-Moves-to-equal-Array-elementsclass Solution {
    public int minMoves2(int[] nums) {
        Arrays.sort(nums);
        int ans = 0;
        int median = nums[nums.length/2];
        for(int num : nums){
            ans += Math.abs(median - num);
            
        }
        return ans;
    }
} 
#6 companies 30 days

