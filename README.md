# OmadenaRasaChatbot


Current issues:


WHILE TRAINING:


C:\Users\Shaifali\anaconda3\envs\install_rasa\lib\site-packages\rasa\shared\utils\io.py:98: UserWarning: Issue found in 'data\rules.yml':
Found intent 'greet' in stories which is not part of the domain.
  More info at https://rasa.com/docs/rasa/stories
C:\Users\Shaifali\anaconda3\envs\install_rasa\lib\site-packages\rasa\shared\utils\io.py:98: UserWarning: Issue found while processing 'data\nlu.yml': The item 'get_info' contains an example that doesn't start with a '-' symbol:
This training example will be skipped.
  More info at https://rasa.com/docs/rasa/training-data-format
C:\Users\Shaifali\anaconda3\envs\install_rasa\lib\site-packages\rasa\shared\utils\io.py:98: UserWarning: Issue found while processing 'data\nlu.yml': The item 'doctor' contains an example that doesn't start with a '-' symbol:
This training example will be skipped.
  More info at https://rasa.com/docs/rasa/training-data-format
2023-02-23 20:39:00 WARNING  rasa.shared.utils.common  - The end-to-end training is currently experimental and might change or be removed in the future 🔬 Please share your feedback on it in the forum (https://forum.rasa.com) to help us make this feature ready for production.
C:\Users\Shaifali\anaconda3\envs\install_rasa\lib\site-packages\rasa\shared\utils\io.py:98: UserWarning: Action 'utter_chitchat' is listed as a response action in the domain file, but there is no matching response defined. Please check your domain.
  More info at https://rasa.com/docs/rasa/responses
C:\Users\Shaifali\anaconda3\envs\install_rasa\lib\site-packages\rasa\shared\utils\io.py:98: UserWarning: Your training data contains an example 'What is your name?...' for the 'chitchat/ask_name' intent. You either need to add a response phrase or correct the intent for this example in your training data. If you intend to use Response Selector in the pipeline, the training may fail.
C:\Users\Shaifali\anaconda3\envs\install_rasa\lib\site-packages\rasa\shared\utils\io.py:98: UserWarning: Your training data contains an example 'May I know your name...' for the 'chitchat/ask_name' intent. You either need to add a response phrase or correct the intent for this example in your training data. If you intend to use Response Selector in the pipeline, the training may fail.
C:\Users\Shaifali\anaconda3\envs\install_rasa\lib\site-packages\rasa\shared\utils\io.py:98: UserWarning: Your training data contains an example 'What do people call ...' for the 'chitchat/ask_name' intent. You either need to add a response phrase or correct the intent for this example in your training data. If you intend to use Response Selector in the pipeline, the training may fail.
C:\Users\Shaifali\anaconda3\envs\install_rasa\lib\site-packages\rasa\shared\utils\io.py:98: UserWarning: Your training data contains an example 'Do you have a name f...' for the 'chitchat/ask_name' intent. You either need to add a response phrase or correct the intent for this example in your training data. If you intend to use Response Selector in the pipeline, the training may fail.
C:\Users\Shaifali\anaconda3\envs\install_rasa\lib\site-packages\rasa\shared\utils\io.py:98: UserWarning: Your training data contains an example 'Will you please be n...' for the 'chitchat/be_nice' intent. You either need to add a response phrase or correct the intent for this example in your training data. If you intend to use Response Selector in the pipeline, the training may fail.
C:\Users\Shaifali\anaconda3\envs\install_rasa\lib\site-packages\rasa\shared\utils\io.py:98: UserWarning: Your training data contains an example 'Would you be nice to...' for the 'chitchat/be_nice' intent. You either need to add a response phrase or correct the intent for this example in your training data. If you intend to use Response Selector in the pipeline, the training may fail.
C:\Users\Shaifali\anaconda3\envs\install_rasa\lib\site-packages\rasa\shared\utils\io.py:98: UserWarning: Your training data contains an example 'Can you stop being s...' for the 'chitchat/be_nice' intent. You either need to add a response phrase or correct the intent for this example in your training data. If you intend to use Response Selector in the pipeline, the training may fail.
C:\Users\Shaifali\anaconda3\envs\install_rasa\lib\site-packages\rasa\shared\utils\io.py:98: UserWarning: You have defined training data with examples for training a response selector, but your NLU configuration does not include a response selector component. To train a model on your response selector data, add a 'ResponseSelector' to your configuration.
  More info at https://rasa.com/docs/rasa/components
C:\Users\Shaifali\anaconda3\envs\install_rasa\lib\site-packages\rasa\shared\utils\io.py:98: UserWarning: You have defined synonyms in your training data, but your NLU configuration does not include an 'EntitySynonymMapper'. To map synonyms, add an 'EntitySynonymMapper' to your configuration.
  More info at https://rasa.com/docs/rasa/components



WHILE TESTING: 

C:\Users\Shaifali\anaconda3\envs\install_rasa\lib\site-packages\rasa\shared\utils\io.py:98: UserWarning: Issue found in '.\tests\test_stories.yml':
Found intent 'greet' in stories which is not part of the domain.
  More info at https://rasa.com/docs/rasa/stories
C:\Users\Shaifali\anaconda3\envs\install_rasa\lib\site-packages\rasa\shared\utils\io.py:98: UserWarning: Issue found in '.\tests\test_stories.yml':
Found intent 'mood_great' in stories which is not part of the domain.
  More info at https://rasa.com/docs/rasa/stories
C:\Users\Shaifali\anaconda3\envs\install_rasa\lib\site-packages\rasa\shared\utils\io.py:98: UserWarning: Issue found in '.\tests\test_stories.yml':
Found intent 'goodbye' in stories which is not part of the domain.
  More info at https://rasa.com/docs/rasa/stories
C:\Users\Shaifali\anaconda3\envs\install_rasa\lib\site-packages\rasa\shared\utils\io.py:98: UserWarning: Issue found in '.\tests\test_stories.yml':
Found intent 'mood_unhappy' in stories which is not part of the domain.
  More info at https://rasa.com/docs/rasa/stories
C:\Users\Shaifali\anaconda3\envs\install_rasa\lib\site-packages\rasa\shared\utils\io.py:98: UserWarning: Issue found in '.\tests\test_stories.yml':
Found intent 'affirm' in stories which is not part of the domain.
  More info at https://rasa.com/docs/rasa/stories
C:\Users\Shaifali\anaconda3\envs\install_rasa\lib\site-packages\rasa\shared\utils\io.py:98: UserWarning: Issue found in '.\tests\test_stories.yml':
Found intent 'deny' in stories which is not part of the domain.
  More info at https://rasa.com/docs/rasa/stories
C:\Users\Shaifali\anaconda3\envs\install_rasa\lib\site-packages\rasa\shared\utils\io.py:98: UserWarning: Issue found in '.\tests\test_stories.yml':
Found intent 'bot_challenge' in stories which is not part of the domain.
  More info at https://rasa.com/docs/rasa/stories
  



C:\Users\Shaifali\anaconda3\envs\install_rasa\lib\site-packages\rasa\shared\utils\io.py:98: UserWarning: Issue found while processing 'data\nlu.yml': The item 'get_info' contains an example that doesn't start with a '-' symbol:
This training example will be skipped.
  More info at https://rasa.com/docs/rasa/training-data-format
C:\Users\Shaifali\anaconda3\envs\install_rasa\lib\site-packages\rasa\shared\utils\io.py:98: UserWarning: Issue found while processing 'data\nlu.yml': The item 'doctor' contains an example that doesn't start with a '-' symbol:
This training example will be skipped.
  More info at https://rasa.com/docs/rasa/training-data-format
C:\Users\Shaifali\anaconda3\envs\install_rasa\lib\site-packages\rasa\shared\utils\io.py:98: UserWarning: Issue found in 'data\rules.yml':
Found intent 'greet' in stories which is not part of the domain.
  More info at https://rasa.com/docs/rasa/stories
  
  
  
  
  THE MODEL RUNS DESPITE THESE ISSUES, HOWEVER, THE CHATBOT ONLY HAS INPUT; PRODUCES NO OUTPUT.
  
  
  
