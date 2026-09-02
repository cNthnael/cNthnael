🌌 Welcome to the Black Hole of Code & Chaos 🌌
"Do or ~~Dropout~~ Unemployed" — A CS Graduate's Survival Saga
🚀 About Me

```python
class CS_Graduate:
    def __init__(self):
        self.status = "Graduated 🎓"  # diploma: 1, job offers: 0
        self.gpa = "Above 3.0. Nobody asked."
        self.job_applications = 247
        self.interviews = 3
        self.offers = 0
        self.resume = "Resume_Final_v2_ACTUALLY_FINAL(3).pdf"
        self.cover_letter = "Dear [COMPANY_NAME], I am excited to apply..."  # ctrl+F, ctrl+V since day 1
        self.diet = "Indomie + copium"
        self.sleep_schedule = "LeetCode grind > REM cycle"

    def apply(self, job):
        if "Entry Level" in job.title and job.min_experience >= 5:
            raise EntryLevelParadoxError("bro it's called ENTRY level")

        self.job_applications += 1
        return self.wait_for_response(job)

    def wait_for_response(self, job):
        try:
            return job.company.respond()
        except GhostedError:
            print("We'll keep your resume on file 🙃")  # narrator: they wouldn't
        except ATSRejectedError:
            print("Bot rejected me for writing 'React.js' instead of 'ReactJS'")
        finally:
            self.copium += 1

me = CS_Graduate()
while me.offers == 0:
    me.apply(random_linkedin_job())
    # this loop has been running since graduation day. send help.
```
