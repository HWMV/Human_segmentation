# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 최현우
- 리뷰어 : 김연


# PRT(Peer Review Template)
- [X]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
>네. 두 어린 아이가 있는 사진에서 배경과 아이들을 분리하셨고, 배경에만 블러처리를 하신 후 다시 아이들과 합성한 사진, 해변 풍경으로 배경을 바꿔서 합성한 사진을 생성하셨으며, 동일한 기법으로 고양이 사진도 생성하셨습니다. 
    
- [X]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**

```
WARNING:tensorflow:6 out of the last 6 calls to <function Model.make_predict_function.<locals>.predict_function at 0x7f79b06f1f70> triggered tf.function retracing. Tracing is expensive and the excessive number of tracings could be due to (1) creating @tf.function repeatedly in a loop, (2) passing tensors with different shapes, (3) passing Python objects instead of tensors. For (1), please define your @tf.function outside of the loop. For (2), @tf.function has experimental_relax_shapes=True option that relaxes argument shapes that can avoid unnecessary retracing. For (3), please refer to https://www.tensorflow.org/guide/function#controlling_retracing and https://www.tensorflow.org/api_docs/python/tf/function for  more details.
```

>위의 경고는 해당 노드 작업 과정에서 모델이나 라이브러리를 가져오면서 나타났던 TensorFlow 오류로 작업 시간이 다소 지체되는 경우에 종종 볼 수 있었습니다. 전체적으로 오류없이 진행되었습니다.
        

- [X]  **3. 에러가 난 부분을 디버깅하여 문제를 “해결한 기록을 남겼거나”, ”새로운 시도 또는 추가 실험을 수행”해봤나요?**
  
>전체적인 작업이 오류없이 진행되었으며, 이미지 합성 후 결과물로 생성된 이미지에서 경계가 모호한 부분과 관련한 문제를 어떻게 해결하면 좋을지 회고에 다양한 솔루션을 제시하셨습니다. 
        


- [ ]  **4. 회고를 잘 작성했나요?**

>네. 

        
- [ ]  **5. 코드가 간결하고 효율적인가요?**

>네. 간결하고 효율적입니다.

# 참고 링크 및 코드 개선

>다양한 사진으로 다이나믹한 프로젝트를 진행하셨고, 각기 다른 사진에서 객체와 배경을 분리한 후 합성하신 과정이 흥미롭습니다. 결과물에 대해 세심하게 관찰하시고 고민하신 내용을 회고에 잘 정리해주셔서 비슷한 문제를 경험한 저도 공감하면서 읽었습니다. 수고하셨습니다!