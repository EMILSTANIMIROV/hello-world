# hello-world

public List<UniversitySubject> getAllSubjects() {
		//If someone change the collection returned by this method, the inner state of the object wont be changed
		List<UniversitySubject> result = new ArrayList<>();
		result.addAll(subjects);

		return result;

	}
