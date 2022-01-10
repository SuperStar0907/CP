> prime Numbers in cp (bracket name is it’s snippet name in vscode)

1. number of co-primes before n (coprime)—>

        ll coprime(ll n)
        {
          ll number = n;
          if (n % 2 == 0)
          {
            number /= 2;
            while (n % 2 == 0)
              n /= 2;
          }
          for (ll i = 3; i <= sqrt(n); i += 2)
          {
            if (n % i == 0)
            {
              while (n % i == 0)
                n /= i;
              number = (number / i * (i - 1));
            }
          }
          if (n > 1)
            number = (number / n * (n - 1));
          return number;
        } // O(sqrt(N))



2.  Euler's totient function for counting number of integers <=n which are coprime to n (totient)—>

        long long phi(long long n)
        {
          long long ans = n;
          for(long long i = 2; i * i <= n; i++)
            if(n % i == 0)
            {
              ans -= ans / i;
              while(n % i == 0)
                n /= i;
            }
          if(n > 1)
            ans -= ans / n;
          return ans;
        }


3.  Simple but smart code to find primes till n (get-primes-upto)—>

        vector<int> get_primes_upto(int n)
        {
          vector<int> composite(n);
          composite[0] = 1;
          for(int i = 2; i <= n; i++)
          {
            if(composite[i-1])
              continue;
            for(int j = 2 * i; j <= n; j += i)
              composite[j-1] = 1;
          }
          vector<int> primes;
          for(int i = 1; i <= n; i++)
            if(!composite[i-1])
              primes.push_back(i);
          return primes;
        }


4.  Prime factors of n in a way of pairs (get-prime-factors)—>

        std::vector<std::pair<int, int>> get_prime_factors(int n)
        {
          std::vector<std::pair<int, int>> ans;
          for(int i = 2; i * i <= n; i++)
          {
            if(n % i == 0)
            {
              int cnt = 0;
              while(n % i == 0)
              {
                n /= i;
                cnt++;
              }
              ans.push_back({i, cnt});
            }
          }
          if(n != 1)
          {
            ans.push_back({n, 1});
          }
          return ans;
        }

