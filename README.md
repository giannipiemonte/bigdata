
# PROJECT BIGDATA

LIVE CORP
You are a young freelance entrepreneur specialized in machine learning. One of your “friends” recommended
you to a company called Live Corp. 

Live Corp is looking for a Freelancer to launch their disease
prediction business. However, this startup is starting from scratch, they clearly need you. 
They have sold the project so well that investors have given several billion euros.

You got the CEO on the phone:
“We want a system to connect to the internet and develop python on a server. Since it’s secure, we also
want you to create a digital intelligence script for us. 

Finally,wewant a small demonstration of breast cancer prediction, we need to mobilize our investors for the next onboarding.”

Luckily the IT development marketing communication intern and community manager sent you an email,
with clearer requests:

“Hi,You must have seen that Lucie F. wasn’t very clear on the subject. I need a **Jupyter Hub with PIP and
sklearn (Tensorflow too if you can install it)**.
We want several accounts for our next intake of interns and alternates.

Lucie also wants you to **get the data from the main RSS feed of Franceinfo**, for our future dataset,
(we want everything in csv format). 

Moreover we also want a small classification of the data in 3 subgroups
science, economy and society. 

I think she told you that she wanted to **make a prediction about possible cases of breast cancer.**

Since our investors are mostly insurance companies, they want to know if we can predict breast cancer and make the insured pay more based on their medical diagnosis. 

If you finish everything before the weekend, you can do a predictive analysis on genes to see if the insured are sick.
Good luck,
Stanislas Anton-Terragulia Almarrillo Nickolavitch”


## Setup

## Windows Support

Summary: On Windows, use `py` instead of `python3` for many of the examples in this documentation.

This package fully supports Windows, along with Linux and macOS, but Python is
typically [installed differently on Windows](https://docs.python.org/3/using/windows.html). Windows
users typically access Python through the [py](https://www.python.org/dev/peps/pep-0397/) launcher
rather than a `python3` link in their `PATH`. Within a virtual environment, all platforms operate
the same and use a `python` link to access the Python version used in that virtual environment.


## Virtual Environments

It is best practice during development to create an
isolated [Python virtual environment](https://docs.python.org/3/library/venv.html) using the `venv`
standard library module. This will keep dependant Python packages from interfering with other
Python projects on your system.

On *Nix:

```bash
# On Python 3.9+, add --upgrade-deps
$ python3 -m venv venv
$ source venv/bin/activate
```

On Windows Powershell / `cmd`:

```bash
> py -m venv venv
> venv\Scripts\activate
```

Once activated, it is a good practice to update core packaging tools (`pip`, `setuptools`,
and `wheel`) to the latest versions.

```bash
(venv) $ python -m pip install --upgrade pip setuptools wheel
```


**Setup - Requirements Install:**

For this particular project, you only need to install the dependencies, to use the project. The dependencies
are listed in the `requirements.txt` file and can be installed by running the following command:

```console
pip install -r requirements.txt
```

After running that command, the dependencies should be installed.
