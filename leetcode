class Solution {
public:
    vector<int> twoSum(vector<int>& nums, int target) {
        int size = nums.size();
        vector<int> indices;
        for ( int index = 0; index < size - 1; index++) {
            for ( int index2 = index + 1; index2 < size; index2++) {
                if ( nums[index] + nums[index2] == target) {
                    indices.push_back(index);
                    indices.push_back(index2);
                    return indices;
                }
            }
        }
    }
};
