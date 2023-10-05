class Solution {
public:
    void rotate(vector<int>& nums, int k) {
        vector<int> last;
        int n=nums.size();
        if(k>=n)
        {
            while(k>=n)
            {
                k=k-n;
            }
        }
        for(int i=n-k;i<nums.size();i++)
        {
            last.push_back(nums.at(i));
        }
        for(int i=0;i<n-k;i++)
        {
            last.push_back(nums.at(i));
        }
        nums=last;
    }
};
